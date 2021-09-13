# 청크 파일 업로드를 위한 예제

Java 서버에 청크 파일 업로드를 보여주는 예제. 클라이언트가 사용하는 [Resumable.js](https://github.com/23/resumable.js), HTML 5 파일 API를 사용하여 청크를 생성합니다.


## Client

요구사항:
- [Node.js](https://nodejs.org/en/download/package-manager/)

실행과정:

    cd client
    npm install
    node app.js

Then browse to [localhost:3000](http://localhost:3000).


## Server

실행과정:

    cd server
    ./mvnw package jetty:run(./run_all.sh)
    
Then browse to [localhost:8002](http://localhost:8002).

...




