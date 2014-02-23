网络编程学习笔记
====

server
  |-> create socket
  |-> bind port
  |-> listen
      |->accept
          |->send, recv
  |-> end
----------------------
clinet
  |-> create socket
  |-> connect to server
        |-> send, recv
  |-> end
