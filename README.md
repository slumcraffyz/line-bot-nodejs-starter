# line-bot-nodejs-starter
starter point to create new line bot project

## How it work
Start express server to handle webhook from LINE

# Install
Clone and run
```
npm install
```
Modify `config.json`
```json
{
  "port" : "3000",
  "channelAccessToken": "1xygwai1tN1659lUO9zu7JMKwYf5f+32eCCYfoTpQMPzPJWoCO0JZvaqd73BJ5SHaKTFpEEev6XPos0JWHX4R/GtiD6DwgjqW60olDs0zZGF9yc9tFjZqcDwLdbBejfE8a8dqAdJW8RexRK59YgPbgdB04t89/1O/w1cDnyilFU=",
  "channelSecret": "cfd77e89c11829ba213c430197e8426d"
}
```
Run
```
npm start
```
then you can access [http://localhost:3000](http://localhost:3000)

Use [ngrok](https://ngrok.com/) to expose your local url
```
path/to/ngrok http 3000
```
config webhook url in developer console then enjoy your bot!

## Author
Sitthi Thiammekha
