# Card Hoster
A simple card hoster built in html, with an unlimited number of pages, and support for background music

## What is this?
- This is a card hoster
- It is built using html, css, and JS
- It can be used to host cards for any occasion on the web, such as for birthdays or anniversaries
- It can be expanded by simple changing one variable

## How do I set this up?
Clone/download the repository. Open up `card/pages` and place each page of the card, naming it 1.png, 2.png, 3.png etc. They should ideally be `.png` files. Canva natively supports exports to this format, and if its in another format, please convert them first.  
Open up `index.html`    
Change the variable on line 127 to however many pages there are in your card.  
I.e.
```
    const totalPages = 5; // Set total number of pages
```

becomes  

```
    const totalPages = 12; // Set total number of pages
```
if you have 12 pages  

If using docker, run `docker compose up -d` to quickly spin up a webserver on port 80.  
  
## Video  

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Xi088-wsaJk/0.jpg)](https://www.youtube.com/watch?v=Xi088-wsaJk)
