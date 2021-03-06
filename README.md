# list-o-regex
###### https://regex101.com/

I kept using this regex tool so often that I wanted to create a list of urls to regular expressions I've collected for various things.  That way I can update them over time and hopefully see them improve as I use them more.

### Rules to this list

Make sure you give a regular expression a name, a description of what it does, and also make sure you save the actual regular expression itself incase the regex101 site decides to drop a database on a bad day.

#### Hours 1-24
^((1[0-9]|2[0-4])|[1-9])$<br />
https://regex101.com/r/Nw1Vg9/3<br />
Matches from numbers 1 to 24 containing nothing else.

#### Simple Address (5 digits)
^\d{5}$<br />
https://regex101.com/r/PExLTl/3<br />
Matches a 5 digit address.

#### SS Number
^\d{3}-\d{2}-\d{4}$<br />
https://regex101.com/r/4UnLRF/1<br />
Matches a standard U.S. social security number.  (i.e 123-456-7891)

#### Date
^(0?[1-9]|1[0-2])\/(0?[1-9]|[1-2]\d|3[0-1])\/[1-2]\d{3}$<br />
https://regex101.com/r/0aATlT/5<br />
Matches a date pattern using '/' dashes.  Will handle patterns like MM/DD/YYYY with optional single digits for month and days.  Requires 4 digits for the year.

#### Letters and numbers
^[a-zA-Z0-9]+?$<br />
https://regex101.com/r/z9Pe5K/1<br />
Matches a string that only contains letters and number characters (no spaces).  Useful for user accounts and it's also optimized to require very few steps.

