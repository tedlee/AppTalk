AppTalk
===

A quick hack to grab iOS AppStore review data.


### How to run. 
Replace APP_ID with your 9 digit AppStore ID Ex) 305479724

For all review:

    python scraper.py -i APP_ID

To specify a country:

    python scraper.py -i APP_ID -c "canada"

**Thanks to:**

- ["Scraping AppStore Reviews" blog by Erica Sadun](http://blogs.oreilly.com/iphone/2008/08/scraping-appstore-reviews.html)
- ["AppStore codes are based on "appstore_reviews" by Jeremy Wohl](https://github.com/jeremywohl/iphone-scripts/blob/master/appstore_reviews)

###Dependencies

Required for running:  
**elementtree**  

    sudo easy_install elementtree

**argparse**  

    sudo easy_install argparse



