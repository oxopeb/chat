Yandex Practicum

Chat application
Application Chatus is intended to provide connection between people.

Figma prototype: 
https://www.figma.com/file/NTjyUDsZBdhUJWAfTwdU8z/Practicum---Sprint-1?node-id=0%3A1

Commands:
<!-- Compile & execute app in realtime -->
"dev": "parcel src/index.html --no-cache --open --port 1234",
<!-- Build static files & execute express server -->
"start": "rm -rf ./dist/* && parcel build src/index.html && node ./server.js",
<!-- Build static files -->
"build": "rm -rf ./dist/* && parcel build src/index.html",
<!-- Execute parcel watch -->
"watch": "parcel watch"