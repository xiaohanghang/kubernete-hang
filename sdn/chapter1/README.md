# TCP/IP网络模型

* 链路层：负责封装和解封包装IP报文，发送和接受ARP/RAPP报文等。
* 网络层：负责路由以及把分组报文发送给目标网络或者主机
* 传输层：负责对报文进行分组和重组，并且以tcp或者udp协议格式封装报文

在网络体系架构中，网络中心的建立必须在通信双方的对等层进行，不能交错，在整个数据传输过程中，数据在发送端时经过各层时都要附加上相应层的协议头和协议尾（仅数据链路层需要封装协议尾）部分，也就是要对整个数据进行协议封装，以标识对应层所用的通信协议。

# osi七层模型

当然在理论上，还有一个OSI七层模型：物理层、数据链路层、网络层、传输层、会话层、表示层和应用层。这是一个理想模型，由于其复杂性并没有被大家广泛采用。



