#SSLCheck via CLI

**sslcheck must have execution permissions**

```
 chmod +x sslcheck
```

Create an alias using .bashrc then you can run it anywhere on command line.

```
vim (or nano?) .bashrc

export set PATH=$PATH:*location of script in this case ->*~/scripts/

```

Example use:

```
sslcheck example.com
```

```
example.com
        Valid From:      3rd Nov 2015 (2015-11-03 00:00:00)
        Valid To:        28th Nov 2018 (2018-11-28 12:00:00)
        Days Left:       216
        Issuer:  DigiCert SHA2 High Assurance Server CA
        Sans:   www.example.org, example.com, example.edu, example.net, example.org, www.example.com, www.example.edu, www.example.net
        CN:     www.example.org
```
