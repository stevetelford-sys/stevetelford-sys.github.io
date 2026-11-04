# stevetelford-sys.github.io

Hosts the public key for a Tesla Fleet API app used by Home Assistant.

The key is served at `/.well-known/appspecific/com.tesla.3p.public-key.pem`. Only the public key belongs here; the private key stays on the Home Assistant server.

`.nojekyll` makes GitHub Pages serve the `.well-known` folder.
