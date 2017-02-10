# tomr-ui
User Interface for TomR

## Setup code base
To setup the code base, create a Git account using this [link] (https://github.com/join)

Download the code using the following command:
```
git clone https://github.com/srm912/tomr-ui.git
```

## Code overview
Currently the base page is __index.html__

## Functionality expected from the UI (in progress)
* Load data:
 There can be two modes here.
  * Either you specify a single key-value combo which gets sent to the store.
  * Or bulk loading at the click of a button, specify number of keys else have a default number
* Query Data: This will require a sub section with a key list
  * Update data
  * Delete data
* Add/remove node
  * Add node will require a container to be booted up within the same container and ready to join the data-node network
  * Remove node will actually be a button accompanying the data nodes on the node-info page.
