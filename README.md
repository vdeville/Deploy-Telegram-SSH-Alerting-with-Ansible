Deploy Telegram SSH Alerting with Ansible
=========================================


**The license doesn't apply to external scripts**

Copyleft (C) Nicolas Simond - 2017

This script is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This script is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this script.  If not, see <http://www.gnu.org/licenses/gpl.txt>


## Usage

Edit the provided **credentials.config** file to add your telegram bot token and ID.

Launch the provided playbook :

<code>ansible-playbook ssh-telegram.yml</code>

* French Blog post -> https://www.abyssproject.net/2017/05/recevoir-alertes-telegram-connexion-ssh/ (not up to date)

## Source
The source script is available here : https://github.com/stylersnico/ssh-login-alert-telegram

This is based on the work of : https://github.com/vdeville/ssh-login-alert-telegram

Thanks to him :)
