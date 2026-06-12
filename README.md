# Camera Tool

A lightweight Flask-based camera upload tool.

## Features

* Browser camera access
* Automatic video upload every 3 seconds
* Uploaded video files are saved in the `uploads/` folder
* Lightweight and easy to deploy
* Supports public access through Cloudflare Tunnel

## Installation

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
pip install -r requirements.txt
python app.py
```

## Cloudflare Tunnel

```bash
cloudflared tunnel --url http://localhost:5000
```


Cloudflare will provide a public HTTPS URL for accessing the application.

## Requirements

* Python 3.x
* Flask
* Cloudflared (optional)

## Author

MHacker
