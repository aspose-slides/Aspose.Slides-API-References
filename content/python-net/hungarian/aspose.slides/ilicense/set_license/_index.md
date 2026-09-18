---
title: set_license method
second_title: Aspose.Slides Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Licenceli a komponenst.


```python
def set_license(self, license_name):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| license_name | **str** | Lehet teljes vagy rövid fájlnév, vagy beágyazott erőforrás neve.<br/><br/>Üres karakterláncot használjon az értékelési módra való váltáshoz. |

### Megjegyzések

Megpróbálja megtalálni a licencet a következő helyeken:


1. Kifejezett útvonal.

2. A komponens összeállítás mappája.

3. Az ügyfél hívó összeállításának mappája.

4. A belépő összeállítás mappája.

5. Beágyazott erőforrás az ügyfél hívó összeállításában.

**Megjegyzés:** .NET Compact Framework esetén csak ezeken a helyeken próbálja megtalálni a licencet:


1. Kifejezett útvonal.

2. Beágyazott erőforrás az ügyfél hívó összeállításában.


## set_license(self, stream) {#iorawiobase}
Licenceli a komponenst.


```python
def set_license(self, stream):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| stream | **io.RawIOBase** | Egy adatfolyam, amely a licencet tartalmazza. |

### Megjegyzések

Használja ezt a metódust licenc betöltéséhez egy adatfolyamból.



### Lásd még
* osztály [`ILicense`](/slides/python-net/hu/aspose.slides/ilicense)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)