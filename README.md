# Semantic comparison app

## Getting Started

- First download and process the initial data.
  ```bash
  python preprocess.py --export_date 'YYYY-MM-DD'
  ```
- Build the app
  ```bash
  docker-compose up -d
  ```
- Activate semantic App
  ```bash
  cd frontend
  npm start
  ```
- Activate App from local
  ```bash
  http://localhost:6868
  account:admin
  password:password
  ```
