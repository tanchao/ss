## Ideas
I don't need too many sales items, but I want to know my selected items are on sales.

## Plan
1. Starts with MUJI, sales apparel items on official website
2. API style
> /ss, super_selection menu, api description
> * /ss/muji, muji sales
> ** format: title, sales, price, (sizes?)
> ** /ss/muji?sex=m&size=xl: muji + male + XL
> ** /ss/gap, gap sales
3. combine with WeChat?

## Design
* configuration oriented, each brand/website has its name, url, regex rule etc.
*

## TODO
- [x] Install requests and beautifulsoup [Done]
    * pip install requests
    * pip install BeautifulSoup4
- [x] Install Flask API website
    * http://www.flaskapi.org/
    * pip install Flask-API
    * pip install markdown
- [ ] Github manage
- [ ] AWS deployment
- [ ] Spider logic implements
    * for MUJI
    * for common

## Setups
* Installations
    * install python, pip
    * pip install requests, BeautifulSoup4, Flask-API, markdown