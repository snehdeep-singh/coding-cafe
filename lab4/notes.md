`--global` sets your name and email for every Git project on your laptop, not just this one. If you skip it, Git only saves your details for this single folder.
The `.git` folder showed up because names starting with a dot are hidden normally. Inside it, Git keeps all the saved history, tracking data and internal setup files for this project.
It shows lots of files, mostly thousands of items inside `.venv`. I didn't write any of those; they are just libraries and setup tools installed by Python.
The entire `.venv` folder and Python temporary cache files disappeared from the list.
Yes, it should be saved and committed. That way, anyone else who downloads the project later will automatically ignore the exact same junk files.
It moved from untracked files to the staged files list. In simple terms, Git now knows about it and lined it up ready to be saved in the next snapshot.
It printed a short ID code the note I wrote and how many files were changed or added in this save.
They are called the short commit ID. They work like a short nickname or receipt number to identify that specific saved checkpoint.
edit your files, check what changed, prepare the files to be saved, and then save the snapshot.
Because `README.md` is standard for every project. Websites like GitHub look for this exact name to show as the welcome page so people know what the folder is about.
It logs your computer into your GitHub account through your browser and saves a login key. Because of that Git already knows who you are and doesn't need your password every time.
The text from `README.md` is showing on the front page. GitHub is built to show this file first so anyone visiting can quickly read what the repository is.
No it didn't change anything on my laptop. It just sent a copy of my local saves over to GitHub.
A private repository is safely backed up on GitHub's website and only people you choose can see it. If it doesn't exist on GitHub at all, it only lives on your own laptop and nobody else can access it.
