# ansible_epam
<br>
<b>task1</b><br>
usage: ansible-playbook -i inventory task1.yml <br>
tags: install_httpd, deinstall_httpd, grub <br>
<br>
<b>task2</b><br>
usage: ansible-playbook -i inventory --vault-password-file=vault_password task2.yml <br>
tags: add_user <br>
Alice password: Alice<br>
Bob password: Bob<br>
Carol password: Carol <br>
<br>