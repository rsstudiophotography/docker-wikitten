Wikitten
========

Wikitten is a small, fast, PHP wiki, and the perfect place to store your notes, code snippets, ideas, etc.

Check out the **[project website](http://wikitten.vizuina.com)** for more details and features.

[![Wikitten](http://wikitten.vizuina.com/screenshot.png)](http://wikitten.vizuina.com)



##

```
cd $HOME/docker/wikitten
```


```
git clone https://github.com/uGeek/docker-wikitten.git
```


```
docker run -d --name=wikitten -v $HOME/docker/wikitten/docker-wikitten:/var/www -p 9000:9000 ugeek/wikitten:amd64
```
