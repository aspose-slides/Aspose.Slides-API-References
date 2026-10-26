---
title: only_load_document_properties property
second_title: Aspose.Slides a Pythonhoz a .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties tulajdonság
Ez a tulajdonság akkor érthető, ha a bemutató fájl jelszóval védett.
            A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni egy titkosított bemutató fájlból, és a jelszót figyelmen kívül kell hagyni.
            A false érték azt jelenti, hogy a teljes titkosított bemutatót a megfelelő jelszó használatával kell betölteni.
            Ha a bemutató nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad.
            Ha egy titkosított fájl dokumentum tulajdonságai nem nyilvánosak, és a tulajdonság értéke true, akkor a dokumentum tulajdonságait nem lehet betölteni, és kivétel keletkezik.
            Olvasás/írás **bool**.

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
* osztály [`LoadOptions`](/slides/python-net/hu/aspose.slides/loadoptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)