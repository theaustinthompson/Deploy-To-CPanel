# Deploy-To-CPanel
Deploy To CPanel

** Remember that this code is case sensitive.

Step 1. Edit server URL
        server: ftp.believeinthompson.com
        
Step 2. Create Secret for username
        username: ${{ secrets.FTP_USERNAME }}
        
Step 3. Create Secret for password
        password: ${{ secrets.FTP_PASSWORD }}
        
Change server directory if necessary.
        server-dir: public_html/
