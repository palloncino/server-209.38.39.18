Connect `ssh root@209.38.39.18`

SSH key is called `ag_server` (`/Users/toni/.ssh/ag-server`)

Here are the apps `/var/www/html`

If the server run slow
```bash
pkill -f cursor-server
rm -rf /root/.cursor-server
rm -rf /tmp/cursor-*
```