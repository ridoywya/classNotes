## 🖥️ Bash \& Linux Cheat Sheet

## **✅ Remember well enough to teach someone else**

Basic Commands



ls

📄 Description: Lists contents of a directory

📌 Example: ls -la → shows all files including hidden ones with details



pwd

📄 Description: Prints the current working directory

📌 Example: pwd → /home/user/documents



cd

📄 Description: Changes the current directory

📌 Examples:



cd /var/log → go to /var/log



cd ~ → go to home directory



cd / → go to root



cd .. → go up one directory



mkdir

📄 Description: Creates a new directory

📌 Example: mkdir projects → creates "projects" folder



rm

📄 Description: Removes files or directories

📌 Example: rm -r oldfolder → deletes folder and contents



cp

📄 Description: Copies files or directories

📌 Example: cp report.pdf /home/user/documents/



mv

📄 Description: Moves or renames files/directories

📌 Example: mv draft.txt final\_draft.txt



cat

📄 Description: Displays contents of a file

📌 Example: cat notes.txt



nano

📄 Description: Edits text files

📌 Example: nano game.sh or nano forest.txt



Package Management



su → Super user



sudo → Super user do



sudo apt-get update

📄 Description: Updates the list of available packages

📌 Example: sudo apt-get update



sudo apt-get upgrade

📄 Description: Upgrades all installed packages

📌 Example: sudo apt-get upgrade



sudo apt-get install <package>

📄 Description: Installs new software

📌 Example: sudo apt-get install nmap



sudo apt-get remove <package>

📄 Description: Removes software

📌 Example: sudo apt-get remove nmap



## **⚠️ Remember but may need some help**

File Permissions \& Ownership



chmod → change file permissions

📌 Examples:



chmod 755 script.sh → owner full, others read/execute



chmod 644 document.txt → owner read/write, others read



chmod 777 folder → everyone full permissions



chown → change file ownership

📌 Example: sudo chown user:group file.txt



ls -l → list files with permissions \& ownership



Process \& System Management



top → real-time process monitor



ps → snapshot of running processes (ps aux → detailed view)



kill <PID> → terminate process



df -h → disk space usage (human-readable)



du -h <folder> → size of files/folders



free -m → memory usage (MB)

touch

📄 Description: Creates an empty file or updates timestamp

📌 Example: touch newfile.txt





## **❓ Don’t remember, but I knew it before**

## **Terminology**



Ethical Hacking: Legal hacking to fix vulnerabilities



Penetration Testing: Simulating attacks to test security



Firewall: Network security barrier



Vulnerability: Weakness in a system



Exploit: Tool or method to take advantage of vulnerability



Patch: Software fix/update



Malware: Malicious software (virus, worm, ransomware)



Zero-Day: Vulnerability exploited before a fix exists



Encryption: Securing data from unauthorized access



IP Address: Device identifier on a network



Port Scanning: Checking which ports are open



Simplified Notes



Comments (#) → ignored by computer, explain code



echo → prints messages to screen



Variables: store values (age\_years)



read -p "Enter age: " age\_years → input



echo $age\_years → display value



if Statement: controls flow based on conditions



\[\[ ! $age\_years =~ ^\[0-9]+$ ]] → checks input isn’t a number



Arithmetic $(( )) → math operations (age\_days=$((age\_years \* 365)))



Exit Codes: exit 1 → stop script with error

