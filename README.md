# 🐳 Docker-Demo

A simple Python Flask application demonstrating how to containerize a project using Docker.

## 📁 Project Structure
```
Docker-Demo/
├── Dockerfile
├── app.py
└── requirements.txt
```
---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/murtuzamaaz/Docker-Demo.git
cd Docker-Demo
```
2. Build the Docker Image
```bash
docker build -t docker-demo .
```
3. Run the Docker Container
```bash
docker run -d -p 5000:5000 docker-demo
```

Then open your browser and visit:
➡️ http://localhost:5000

📝 Files Explained
app.py – A basic Flask web server.

requirements.txt – Lists the Python dependencies (e.g., Flask).

Dockerfile – Instructions for building the Docker image.

📦 Example Output
When running, you should see output like:

```
* Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
And visiting http://localhost:5000 should return:
```


Hello, this is a Dockerized Flask App!
🧼 To Stop and Remove Container
```bash
docker ps        # Find the container ID
docker stop <container_id>
docker rm <container_id>
```
📚 Learn More
Docker Official Docs:https://docs.docker.com/get-started/

Flask Documentation:https://flask.palletsprojects.com/en/stable/
