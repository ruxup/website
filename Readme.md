docker build -t radityasurya/ruxup-frontend
docker run -ti -d -p "80" -v $(pwd)/sample:/usr/share/nginx/html .
