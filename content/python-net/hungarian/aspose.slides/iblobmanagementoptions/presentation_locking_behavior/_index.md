---
title: presentation_locking_behavior property
second_title: Aspose.Slides Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior tulajdonság
Ez a tulajdonság meghatározza, hogy a Presentation osztály egy példánya lehet-e a forrás – fájl vagy adatfolyam tulajdonosa az élettartama alatt. Ha a példány tulajdonos, akkor zárolja a forrást. Ez segít csökkenteni a memóriahasználatot és javítja a teljesítményt BLOB-ok kezelésekor, de a forrás (adatfolyam vagy fájl) nem módosítható a Presentation példány élettartama alatt. Íme egy példa:

### Definíció:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### Lásd még
* osztály [`IBlobManagementOptions`](/slides/python-net/hu/aspose.slides/iblobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)