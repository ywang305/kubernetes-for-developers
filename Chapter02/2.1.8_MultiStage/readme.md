```sh
$ cd Chapter02/2.1.8_MultiStage
$ docker build . -t compiled_code2
$ docker run compiled_code2
Hello Docker
```

If we run the ls command on this new container, we can see that there is only the compiled code:

```sh
$ docker run compiled_code2 ls
Hello.class
```

![alt text](image.png)
