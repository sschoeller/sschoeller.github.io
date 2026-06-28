 <h1>How to MS-ify Ubuntu</h1>
 <h3>A Non-satirical Guide</h3>
  <br>
  <p>Abstract: This guide assists in making your Ubuntu system more compatible with MS products that you could encounter at work. It also assumes your admins allow Ubuntu and that you know their policy on that.</p>
  <br>
  <br>
  1. Enable the Multiverse repository (in Software &amp; Updates) &amp; install the MS Fonts<br>
  # apt install ttf-mscorefonts-installer<br>
  2. Install dotnet (version 10.x as of 26.04 LTS).<br>
  # apt install dotnet10<br>
  3. Install wine64<br>
  # apt install wine64<br>
  4. Install PowerShell<br> 
  <a href="https://learn.microsoft.com/en-us/powershell/scripting/install/linux-overview?view=powershell-7.6#ubuntu">Instructions here</a><br>
  5. Install ADsys and related components (Ask your work IT for assistance, this could get tricky!!)<br>
  # apt install adsys krb5-user libsss-sudo
