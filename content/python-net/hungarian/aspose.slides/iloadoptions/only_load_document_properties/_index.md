---
title: only_load_document_properties property
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties tulajdonság
Ez a tulajdonság akkor értelmes, ha a prezentációfájl jelszóval védett.
            A true érték azt jelenti, hogy csak a dokumentum tulajdonságokat kell betölteni egy titkosított 
            prezentációfájlból, és a jelszót figyelmen kívül kell hagyni.
            A false érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő 
            jelszó használatával kell betölteni.
            Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad.
            Ha egy titkosított fájl dokumentum tulajdonságai nem nyilvánosak, és a tulajdonság értéke true, akkor
            a dokumentum tulajdonságok nem tölthetők be, és kivétel lesz dobva.
            Olvasás-írás **bool**.

### Definíció:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Lásd még
* osztály [`ILoadOptions`](/slides/python-net/hu/aspose.slides/iloadoptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)