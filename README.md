# Ansible-playbook-sample
AnsibleのPlaybookサンプル集です。

## playbook
### roles
- all.yml　全てのロールを実行するPlaybook
- local-test インベントリファイル
#### goss
[Goss](https://github.com/aelsabbahy/goss)をインストールします。
#### restart_httpd
Apache(httpd)の再起動を行います。バッチジョブの代わりに利用することを想定しています。  
**usage:**

```$ ansible-playbook -i local-test all.yam -t httpd-restart```
