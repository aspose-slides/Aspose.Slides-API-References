---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded tulajdonság
Ez a tulajdonság akkor értelmezhető, ha a prezentációfájl jelszóval védett és ennek a fájlnak a dokumentumtulajdonságai nyilvánosak.
A true érték azt jelenti, hogy csak a dokumentumtulajdonságok töltődnek be egy titkosított prezentációfájlból jelszó használata nélkül.
A false érték azt jelenti, hogy a teljes titkosított prezentáció betöltődik a helyes jelszó használatával, nem csak a dokumentumtulajdonságok töltődnek be.
Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig false.
Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak, akkor a tulajdonság értéke mindig false.
Ha a PresentationEx.EncryptDocumentProperties true, akkor az IsOnlyDocumentPropertiesLoaded tulajdonság értéke mindig false.
Csak olvasható **bool**.

### Definíció:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Lásd még
* osztály [`IProtectionManager`](/slides/python-net/hu/aspose.slides/iprotectionmanager)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)