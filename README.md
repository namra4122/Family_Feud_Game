# Family Feud using Node.js Express & Socket.io

This is an experiment to create a server with a live socket to set up a **game host instance** and an **audience display instance** for a web app.  Once the host is selected, they will control the audience board and points.  

## Install and start

```bash
git clone https://github.com/namra4122/Family-Feud.git
cd Family-Feud
npm install
npm start
```

Terminal should respond with:

```bash
Listening on 8080
```

## Play Family Feud

* Open two browser windows at http://localhost:8080/
* Click **Be the host** to assign that window to become the game **host controller**. All other open instances will become the **audiance window** window. 
* As the **host** you can:
   * click to reveal answers
   * assign points
   * go to new questions

### Default instance:
![Default instance](public/img/Default.jpg)

### Host instance:
![Host instance](public/img/Host.jpg)

### Audience instance:
![Host instance](public/img/Audience.jpg)

