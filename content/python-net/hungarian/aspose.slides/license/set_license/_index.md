---
title: set_license method
second_title: Aspose.Slides Pythonhoz a .NET API Referencián keresztül
description: 
type: docs
url: /hu/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
Licenceli az összetevőt.


```python
def set_license(self, license_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| license_name | **str** | Lehet teljes vagy rövid fájlnév, vagy beágyazott erőforrás neve.<br/><br/>Üres karakterlánc használatával kapcsolhat értékelési módra. |

### Megjegyzés

Megpróbálja megtalálni a licencet a következő helyeken:


1. Kifejezett útvonal.

2. Az összetevő összeállításának mappája.

3. Az ügyfél hívó összeállításának mappája.

4. A belépési összeállítás mappája.

5. Beágyazott erőforrás az ügyfél hívó összeállításában.

**Megjegyzés:** A .NET Compact Framework esetén a licencet csak a következő helyeken keresi:


1. Kifejezett útvonal.

2. Beágyazott erőforrás az ügyfél hívó összeállításában.


## set_license(self, stream) {#iorawiobase}
Licenceli az összetevőt.


```python
def set_license(self, stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Az a folyam, amely a licencet tartalmazza. |

### Megjegyzés

Használja ezt a metódust a licenc betöltéséhez egy folyamról.



### Lásd még
* osztály [`License`](/slides/python-net/hu/aspose.slides/license)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)