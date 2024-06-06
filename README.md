# K2_Metalign

Adds Kraken2 Functionality to Metalign as a Prefiltering step instead of kmc+cmash

Everything else you need:

https://github.com/DerrickWood/kraken2

https://github.com/jenniferlu717/Bracken
https://github.com/nlapier2/Metalign

Manual:
1. Install all the aforementioned. 
2. Add k2_metalign.py and k2_select_db.py to the 'scripts' directory within the Metalign directory
3. Run them using the K2 argument and then either the K2_results argument if you already have a Kraken2 report or the K2_db argument if you need to run Kraken2 first
