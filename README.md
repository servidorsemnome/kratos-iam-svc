<h1 align="center">
  <img src="https://i.imgur.com/5s2wZa6.png" />
  <br/>
  Kratos
</h1>

<p align="center">
  Next-generation identity and access manager service powered by <a href="https://github.com/ory/kratos">Ory Kratos</a>.
</p>

## Installing
Add this line to your `/etc/hosts` (Linux) or `%WinDir%\System32\Drivers\Etc\hosts` (Windows) file:
```sh
127.0.0.1 local.ssn.gg
```

## Running
```sh
docker-compose up --build
```

The API will be available at [local.ssn.gg:4433](http://local.ssn.gg:4433) for browser clients but also at [kratos:4433](http://kratos:4433) for other servers on the same network.
