---
title: CreateXmlDeclaration()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy XmlDeclaration csomópontot a megadott értékekkel.
type: docs
weight: 378
url: /hu/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) metódus


Létrehoz egy [XmlDeclaration](../../xmldeclaration/) csomópontot a megadott értékekkel.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | A verzió csak \"1.0\" lehet. |
| encoding | const [String](../../../system/string/)\& | Az encoding attribútum értéke. Ez a kódolás, amelyet akkor használ, amikor a [XmlDocument](../)-t fájlba vagy adatfolyamba menti; ezért egy, a [Text::Encoding](../../../system.text/encoding/) osztály által támogatott karakterláncra kell beállítani, különben az \"XmlDocument::Save(String)\" hibát eredményez. Ha ez **nullptr** vagy [String::Empty](../../../system/string/empty/), a [XmlDocument::Save](../save/) metódus nem ír encoding attribútumot az XML deklarációra, ezért az alapértelmezett kódolás, az UTF-8, lesz használva. |
| standalone | const [String](../../../system/string/)\& | Az értéknek \"yes\" vagy \"no\" kell lennie. Ha ez **nullptr** vagy [String::Empty](../../../system/string/empty/), a [XmlDocument::Save](../save/) metódus nem ír standalone attribútumot az XML deklarációra. |

### Visszatérési érték

Az új [XmlDeclaration](../../xmldeclaration/) csomópont.

## Megjegyzések



Megjegyzés: Ha a [XmlDocument](../) egy TextWriter-be vagy egy [XmlTextWriter](../../xmltextwriter/)-ba van mentve, ez az encoding érték elvetésre kerül. Ehelyett a TextWriter vagy a [XmlTextWriter](../../xmltextwriter/) kódolása kerül felhasználásra. Ez biztosítja, hogy a kiírt XML a megfelelő kódolással olvasható vissza.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlDeclaration](../../xmldeclaration/)
* Osztály [String](../../../system/string/)
* Osztály [XmlDocument](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)