# nodejssample

## Usage
1. install node.js
<pre>
>choco install -y nodejs
</pre>

1. install ws

<pre>
>npm install ws
</pre>

1. install wscat 
<pre>
>npm install wscat
</pre>


## Test
server
<pre>
>node app.js
</pre>

client
<pre>
> wscat -c ws://localhost:8081
</pre>