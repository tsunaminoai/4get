4get
========

An image downloader for 4chan.

========

Description:

4get is a utility writing in bash script which will download all images in a given thread from 4chan specifically and potentially other waka-style imageboards

4get will download all images to a folder with the thread's ID. Running 4get again will download any subsequent posts from that thread into the folder. When the thread expires or is removed, 4get will no longer update that thread.

========

Usage:

4get [thread url]


Running with [thread url] will download/update only the thread in the url.

Running without a specified url will force 4get to search the directories in the current folder for previous 4get fetches and check them for updates.
