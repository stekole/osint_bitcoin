# osint_bitcoin
opensource intelligence on miners


# search-shodan.py
This script is used to search shodan for whatever search you would like 

   ``` usage: search_shodan.py [-h] [-a APIKEY] [--search SEARCH] [--page PAGENUMBER] ```


   -a --apikey   =    Your api key 
   
   -s --search   =    Your search terms
   
   -p --page     =    Page number you want to return 
   
   
feel free to pipe to a file

    example:  python search_shodan.py --page 2 --search "Server: LINUX/2.4 UPnP/1.0 BRCM400/1.0" >> list.txt 
   
   
