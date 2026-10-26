---
title: set_metered_key method
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
Beállítja a méréshez használt nyilvános és privát kulcsot.
            Ha mérés alapú licencet vásárol, az alkalmazás indításakor ezt az API-t kell meghívni, általában ez elegendő. 
            Azonban ha folyamatosan sikertelen az adatfelhasználás feltöltése, és 24 órán túl tart, a licenc értékelési állapotra kerül, 
            ezen eset elkerülése érdekében rendszeresen ellenőrizze a licenc állapotát; ha értékelési állapotú, hívja újra ezt az API-t.


```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| public_key | **str** | nyilvános kulcs |
| private_key | **str** | privát kulcs |



### Lásd még
* osztály [`Metered`](/slides/python-net/hu/aspose.slides/metered)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)