# scholar-crawler
An scrapy based web crawler to scrap google scholars website and export the results in a csv file.

## Installation and Requirements

*Most Linux based OS have python3 installed, in case you don't have it, you can install it by*
`sudo apt install python3`

Once, python3 is installed and configured. You can clone this repository by executing `git clone https://github.com/sarthak-patidar/scholar-crawler.git .` from the terminal or download the zip and extract it.

Now, open the terminal and cd into the directory where you have cloned the repository or extracted the zip and execute the following commands.

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

The installation of requirements should go without any errors, but in case you see a error, you might need to install `wheel` by
`pip install wheel` and then execute `pip install -r requirements.txt` again.

## Running the spider

Once the installation is over, you can run the spider by executing following command from the root project directory.

`scrapy crawl gscrawler`

After scraping is done, the results are exported into `results.csv` file which is created in the root directory itself.


## Reporting Issues

If you see any errors or have any suggestions, you can [create an issue](https://github.com/sarthak-patidar/scholar-crawler/issues).
