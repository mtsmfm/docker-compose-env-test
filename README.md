```
$ cd /path/to/root
$ docker compose run --rm test
FOO: root
$ cd ./foo
$ docker compose run --rm test
FOO: foo
$ cd ../bar
$ docker compose run --rm test
FOO: root
```
