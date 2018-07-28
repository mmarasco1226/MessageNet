# msg_blockchain

Developing a blockchain application from scratch in Python



### Instructions to run

Start a blockchain node server,

```sh
>>> python node_server.py
```

Run our application,

```sh
>>> python run_app.py
```

The application should be up and running at [http://localhost:5000](http://localhost:5000).



To play around by spinning off multiple custom nodes, use the `add_nodes/` endpoint to register a new node. To update the node with which the application syncs, change `CONNECTED_NODE_ADDRESS` field in the [views.py](https://github.com/satwikkansal/ibm_blockchain/blob/master/app/views.py) file.
