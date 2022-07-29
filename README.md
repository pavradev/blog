# Descripton
Personal blog

### Converting mermaid diagrams into png in docker

    docker run --rm -it -v /path/to/diagrams:/data minlag/mermaid-cli -i /data/diagram.mmd diagram.png


Ream more [here](https://github.com/mermaid-js/mermaid-cli)
