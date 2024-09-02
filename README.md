# Webscraping

In this task, I tried to scrape marketing relevant information from both list and product pages on 3 different websites. A list page is one containing more than one product, while a product page is one dedicated to a product. 

Considering the following list page URLs:

https://www.missetam.nl/nl/collectie/jurken/

https://www.gap.com/browse/category.do?cid=5664&nav=meganav%3AWomen%3ACategories%3AJeans#pageId=0&department=136

https://www.your-look-for-less.nl/goedkope-blouses

For the first 10 products on these list pages, I obtained the following information available on the list page:

- Product name
- Price
- Discounted price
- Position

Considering the following product page URLs:

https://www.missetam.nl/nl/3844173/top-print-zwart/

https://www.gap.com/browse/product.do?pid=794603002&rrec=true&mlink=5001,1,dynamicerror_gapoos1_rr_2&clink=1#pdp-page-content

https://www.your-look-for-less.nl/p/99055


And for the following product page URLs, additionally obtained:

- Brand
- Number of photos
- Colors
- Product description

I arranged the output in a csv file as follows:
URL, list/product page, product name, brand, price, discounted price, position, number of photos, number of colors, product description.
