The File Transfer Protocol (FTP) is one way to get and transfer files between computers. The protocol is one of the oldest methods that is still used today; its early development started in 1971. It was developed as a mechanism for granting access to users so that they could access and use files on a specific system.
FTP is a method to access and share files on the internet. The protocol is a way to communicate between computers on a TCP/IP network, the internet.  It’s used by users who have access to transfer and receive files in the FTP server (also known as FTP host/site). The access control is essential to prevent an unauthorized person from getting those files.
How does FTP work?
FTP connection needs two parties to establish and communicate on the network. To do that, users need to have permission by providing credentials to the FTP server. Some public FTP servers may not require credentials to access their files. The practice is common in a so-called anonymous FTP.
There are two distinct communication channels while establishing an FTP connection. The first one is called the command channel where it initiates the instruction and response. The other one is called a data channel, where the distribution of data happens.
To get or transfer files, an authorized user will use the protocol to request on creating changes in the server. In return, the server will grant that access. This session is known as the active connection mode.

How to use FTP
There are three approaches on how to establish an FTP connection. A  very simple method is using a command line FTP, such as using Command prompt for Windows or Terminal in Mac/Linux. Developers still use it today for transferring files using FTP.

A user also can use a web browser to communicate with the FTP server. A web browser is more convenient when users want to access large directories in the server. Yet, it’s often less reliable and slower than using a dedicated FTP program.

Today, the most common practice to use FTP, especially for a web developer, is by using an FTP client.

An FTP client provides more freedom compared to the command line and web browser. It is also easier to manage and more powerful compared to the other methods.

There are also more features available whilst using such a client. For example, it allows users to transfer large files and use the synchronizing utility.
The first FTP client applications were command-line programs developed before operating systems had graphical user interfaces, and are still shipped with most Windows, Unix, and Linux operating systems. Many FTP clients and automation utilities have since been developed for desktops, servers, mobile devices, and hardware, and FTP has been incorporated into productivity applications, such as HTML editors.
FTP was not designed to be a secure protocol, and has many security weaknesses. In May 1999, the authors of RFC 2577 listed a vulnerability to the following problems:
Brute-force attack
FTP bounce attack
Packet capture
Port stealing (guessing the next open port and usurping a legitimate connection)
Spoofing attack
Username enumeration
DoS or DDoS
FTP does not encrypt its traffic; all transmissions are in clear text, and usernames, passwords, commands and data can be read by anyone able to perform packet capture (sniffing) on the network.  This problem is common to many of the Internet Protocol specifications (such as SMTP, Telnet, POP and IMAP) that were designed prior to the creation of encryption mechanisms such as TLS or SSL.
