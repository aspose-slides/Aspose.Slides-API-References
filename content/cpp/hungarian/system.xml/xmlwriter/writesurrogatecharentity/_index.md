---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides C++ API Referencia
description: Amikor egy származtatott osztályban felül van definiálva, előállítja és kiírja a szurrogát karakterpár szurrogát karakter entitást.
type: docs
weight: 261
url: /hu/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) method

Amikor egy származtatott osztályban felül van definiálva, előállítja és kiírja a szurrogát karakterpár szurrogát karakter entitást.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lowChar | char16_t | Az alacsony szurrogát. Ennek 0xDC00 és 0xDFFF közötti értéknek kell lennie. |
| highChar | char16_t | A magas szurrogát. Ennek 0xD800 és 0xDBFF közötti értéknek kell lennie. |

## Lásd még

* Osztály [XmlWriter](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)