# metadata
This repository contains drama meta data

## drama.tsv
The file is tab-separated.
Each line contains a textgrid id and a list of genre tags. The genre tags are to be separated by comma, as shown in the first line.

To find the drama for an id, add the id into the following URL, but replace the dot with an underscore. The URL for xknr.0 would be 
https://textgridrep.org/browse/-/browse/xknr_0, for instance.
To retrieve the TEI xml for a drama, go to 
https://textgridlab.org/1.0/tgcrud-public/rest/textgrid:xknr.0/data (again, for xknr.0 as an example).