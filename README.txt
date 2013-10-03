
google Drive api -https://developers.google.com/drive/v1/reference/
Drop box Api- https://www.dropbox.com/developers
Box .net API link  http://developers.box.com/

 think our critical components are as follows:
1. Login token (Dropbox)
2. Login token( box.net or gdrive)
3. Show folder structure and indicate the source(dropbox, gdrive)
4. HTML 5 file drag and drop component
5. Dropbox integration for posting a file to dropbox
6. Dropbox search module(parsing the file name, type and source as dropbox)
7. Box.net/Gdrive integration for posting a file to dropbox
8. Box.net/Gdrive search module(parsing the file name, type and source as dropbox)
9. Integration of all the components
10. UI cosmetic changes

Also, while we code our stuff in three different locations we need think about the integration part as well. 

http://cloudgator.herokuapp.com/user/login