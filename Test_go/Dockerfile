FROM golang:1.20

ENV APP_NAME app

COPY . /go/src/${APP_NAME}
WORKDIR /go/src/${APP_NAME}
RUN go get ./
RUN go build -o ${APP_NAME}
CMD ["./app"]
