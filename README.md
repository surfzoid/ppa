# ppa
Add a debian repository, to use it, do :
curl -s --compressed "https://surfzoid.github.io/ppa/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/surfzoidppa.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/surfzoid_list_file.list "https://surfzoid.github.io/ppa/surfzoid_list_file.list"
sudo apt update
sudo apt install qtvsplayer

# Funding
If you like my job and be happy to buy me a beer or a coffee: https://paypal.me/EricPetit
or
https://fr.tipeee.com/eric-utopiste
