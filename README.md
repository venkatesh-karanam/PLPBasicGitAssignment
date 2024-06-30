# PLPBasicGitAssignment

Change Directory:

bash
Copy code
cd e:/
List Directory Contents:

bash
Copy code
ls
Navigate to the Project Directory:

bash
Copy code
cd PLPBasicGitAssignment
Clone the GitHub Repository:

bash
Copy code
git clone https://github.com/venkatesh-karanam/PLPBasicGitAssignment.git
Change Directory to the Cloned Repository:

bash
Copy code
cd PLPBasicGitAssignment
Initialize Git Repository:

bash
Copy code
git init
Add Remote Repository:

bash
Copy code
git remote add origin https://github.com/your-username/PLPBasicGitAssignment.git
Error: Remote origin already exists.
Verify Remote Repository:

bash
Copy code
git remote -v
Create and Write to hello.txt:

bash
Copy code
echo "Hello, Git!" > hello.txt
List Directory Contents to Verify File:

bash
Copy code
ls
Stage the hello.txt File:

bash
Copy code
git add hello.txt
Commit the Changes:

bash
Copy code
git commit -m "Add hello.txt with a greeting"
Push the Changes to GitHub:

bash
Copy code
git push -u origin main
Rename Local Branch to main:

bash
Copy code
git branch -M main





