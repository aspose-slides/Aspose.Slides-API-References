---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides a Pythonhoz a .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded tulajdonság
Ez a tulajdonság akkor értelmezhető, ha a prezentációs fájl jelszóval védett, és a fájl dokumentum tulajdonságai nyilvánosak.
A true érték azt jelenti, hogy csak a dokumentum tulajdonságok töltődnek be egy titkosított prezentációs fájlból jelszó használata nélkül.
A false érték azt jelenti, hogy a teljes titkosított prezentáció betöltődik a megfelelő jelszó használatával, nem csak a dokumentum tulajdonságok töltődnek be.
Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig false.
Ha egy titkosított fájl dokumentum tulajdonságai nem nyilvánosak, akkor a tulajdonság értéke mindig false.
Ha a Presentation.EncryptDocumentProperties true, akkor az IsOnlyDocumentPropertiesLoaded tulajdonság értéke mindig false.
Csak olvasható **bool**.

### Definíció:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Lásd még
* osztály [`ProtectionManager`](/slides/python-net/hu/aspose.slides/protectionmanager)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)