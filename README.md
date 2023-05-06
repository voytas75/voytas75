# Welcome to my GitHub!

```powershell
# Initializing system administrator
$username = "sysadmin"
$techStack = ("M365", "Azure", "AD")
$interests = ("PowerShell", "Sci-Fi books")

# Creating user profile
$userProfile = New-Object -TypeName PSObject
$userProfile | Add-Member -Type NoteProperty -Name "Name" -Value "John Doe"
$userProfile | Add-Member -Type NoteProperty -Name "Username" -Value $username
$userProfile | Add-Member -Type NoteProperty -Name "Tech Stack" -Value $techStack
$userProfile | Add-Member -Type NoteProperty -Name "Interests" -Value $interests

$_welcome = @"
Welcome to my GitHub, fellow programmers!

As a system administrator, I specialize in $techStack, utilizing the power of $interests 
to make my work more efficient.

I am particularly passionate about PowerShell, and I believe that it is a crucial tool 
for managing modern IT systems.

In my free time, I love to indulge in sci-fi books, which often inspire me with new ideas 
and concepts that I can bring into my work.

Feel free to take a look at my projects and contributions, and please don't hesitate to reach 
out if you have any questions or suggestions for collaboration.
"@

Write-Host $_welcome

# Signing off
Write-Host "Live long and prosper 🖖"
```

&nbsp;

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/A0A6KYBUS)

&nbsp;
