# If you have n8n installed: Install custom nodes module

Install it to the n8n root folder. This is the node_modules folder on the same level of n8n and n8n-core. This differs when you used the -g flag on n8n initial installation. From there do:
```
npm install @dataaegis/n8n-node-aritic
```
# Fresh install n8n

Navigate to desired folder, create a package json and install n8n like so:

```
cd /var/www/vhosts/

mkdir my-n8n && cd my-n8n

npm init --yes

npm install n8n

npm install @dataaegis/n8n-node-aritic
```
# Start n8n

Directly:
```
n8n
```

Plesk or C-Panel:
```
node /var/www/vhosts/n8n/bin/n8n
```

# Latest functionality

Eloqua node includes Endpoints for Contacts, Custom Objects and Custom Object Data

# Contribution

To make this node even better, please let us know, [how you use it](mailto:developers@aritic.com). Commits are always welcome.

# Issues

If you have any issues, please [let us know on GitHub](https://github.com/premhunt/n8n-nodes-aritic/issues).

# About
Special thanks to [N8n nodemation](https://n8n.io) workflow automation by Jan Oberhauser.

Nodes by [aritic.com](https://aritic.com). For productive use and consulting on this, [contact us please](mailto:developers@aritic.com).

This node was programmed with :heart: by aritic [premhunt](https://github.com/dataaegis)
