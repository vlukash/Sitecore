# Indexing Events patch for Sitecore 8.1 rev. 151207 (Update-1) 

Indexing events, like:
* *indexing:start*
* *indexing:end*

are not raised when re-indexing is started by *Control Panel* -> *Indexing* -> *Index Manager* tab

The issue can be solved by enabling patch:

1. Place the *Sitecore.Support.406929.dll* assembly into the Bin folder;
2. Place the *IndexingManager.xml* file into the Website\sitecore\shell\Override folder;

Thanks to Sitecore support for providing this patch!
