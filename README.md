```yaml
size: 4.397 gb
compileTime: 30 mins
```

#### Introduction

Based on [mottosso/mayabase-centos][1].

[1]: https://gist.github.com/mottosso/a7f82e97b5ba31da0b38

#### Installation

```bash
$ git clone https://gist.github.com/b950978793f4e85d643f.git maya-centos && cd maya-centos
$ docker build -t mottosso/maya-centos .
```

#### Usage

```bash
$ docker run -ti --rm mottosso/maya-centos mayapy
Python 2.7.3 (default, Aug  2 2012, 13:44:14)
[GCC 4.1.2] on linux2
Type "help", "copyright", "credits" or "license" for more information.
>>> 
```

#### Known issues

1. The `xgenm` module is not available.
2. The `Unfold3D` is not available.