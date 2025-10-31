<h2>Hi there!</h2>
This repo contains reference of how to put a Html website on Internet.

GitHub Pages - Lets us put websites created with HTML, CSS, and JavaScript code on the Internet

Step By Step:
1. Write the code for your website as normal
2. In GitHub create a repo and upload your files here. (Commit changes)
   
   ❌ Don't drag the folder containing all your code into GitHub
   
   ✅ First open the folder, then select all your code and drag and drop into GitHub
4. Go to Settings, then Pages
5. Select Branch: main and click Save.
6. You can add /filename.html to your webpage name OR change your file name to index.html
<hr>

Set up a Domain Name:

1. Purchase a domain from a domain registrar (Namecheap, domain.com, Google Domains, etc.)
2. Go to GitHub Pages IP address. Then go to https://mxtoolbox.com/DNSLookup.aspx (DNS Lookup) and write "[your_github_username].github.io"
<hr>

Create DNS Records:
1. Log into your domain registrar > open the "Settings" for your domain.
2. Create an A Record = links a domain name to an IP address
3. Create a CNAME Record = links a domain name to another domain name. Set up the subdomain "www" (www.mywebsite.com). This is recommended by GitHub Pages.
<hr>

Set up Domain Name in GitHub Pages:
1. In the "Custom domain" section, enter your domain name. Click Save
2. Wait for GitHub's process to finish. Then check the box to activate HTTPS. HTTPS encrypts all data flowing between your browser and your website.
