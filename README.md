# website-demo
This is my first repository
<br>
Author Name Tooba Hoorain



wget --mirror --convert-links --adjust-extension --page-requisites --no-parent https://wallosapp.com/


Step-by-Step Commands (Git Bash)
mkdir offline_sites
cd offline_sites
wget --mirror --convert-links --adjust-extension --page-requisites --span-hosts --domains=trackmysubs.com,www.trackmysubs.com,cdn.trackmysubs.com --no-parent --execute robots=off --user-agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64)" --wait=1 --random-wait --no-clobber --restrict-file-names=windows https://trackmysubs.com/
cd trackmysubs.com
python3 -m http.server 8000
open in browser:
👉 http://localhost:8000
