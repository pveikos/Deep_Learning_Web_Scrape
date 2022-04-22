# Web Scraping code for AllRecipes

This code should scrape recipes from AllRecipes, write them out to a text file, and save the corresponding image of that recipe to the current directory.

The recipes can then be scraped for the ingredients themselves, and saved out to another text file.

Both a requirements.txt file and a environment.yml file are included for my environment.

All you should need to do is run the web_scrape notebook, which will download the images and create Recipes.txt, then run the text_prepro notebook to get a list of the image filepaths and their ingredients.