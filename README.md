# Instructions

1. Open **index.html**, update your pushbots application Id and domain URL:

```javascript
//PushBots ApplicationId (required)PB.app_id = "";
//Your domain name, must be HTTPS or localhost  (required)
PB.domain = "https://www.";
```


2. Open **pushbots-push-manifest.json**, update your google Project number in gcmsenderid field.

3. open **pushbots-worker.js** and add your pushbots application Id. 
-----------------------------
To set alias or tags for your users:


```javascript
PB.q.push(["tag", ['test', "test3"]]);
PB.q.push(["alias", "username"]);
PB.q.push(["untag", ['test', "test3"]]);
```
