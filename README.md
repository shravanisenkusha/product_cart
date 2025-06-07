# product_cart
https://hub.docker.com/repository/docker/shravanipatil21/products/tags
docker build -t shravanipatil21/products:v1.0.0 --build-arg APP_NAME="SHRAVANI" .
docker push shravanipatil21/products:v1.0.0
docker pull shravanipatil21/products:v1.0.0
docker run -p 8000:8000 shravanipatil21/products:v1.0.0
