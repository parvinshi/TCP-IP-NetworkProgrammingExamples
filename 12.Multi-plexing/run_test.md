```
select_serv.c
$ gcc select_serv.c -o serv
$ ./serv 9190
connected client: 4
connected client: 5
closed client: 5 
closed client: 4
```

```
echo_client.c 1
$ gcc echo_client.c -o cli
$ ./cli 127.0.0.1 9190
Connected...
Input message(Q to quit): Hi
Message from server: Hi
Input message(Q to quit): Good Bye
Message from server: Good Bye
Input message(Q to quit): Q
```

```
echo_client.c 2
$ ./cli 127.0.0.1 9190
Connected...
Input message(Q to quit): Nice to meet you
Message from server: Nice to meet you
Input message(Q to quit): Bye
Message from server: Bye
Input message(Q to quit): Bye
Message from server: Bye
Input message(Q to quit): Q
```
