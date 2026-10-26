---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza és írja a helyettesítő karakterentitást a helyettesítő karakterpárhoz.
type: docs
weight: 391
url: /hu/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) metódus

Létrehozza és írja a helyettesítő karakterentitást a helyettesítő karakterpárhoz.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| lowChar | char16_t | Az alacsony helyettesítő. Ennek **0xDC00** és **0xDFFF** közötti értéknek kell lennie. |
| highChar | char16_t | A magas helyettesítő. Ennek **0xD800** és **0xDBFF** közötti értéknek kell lennie. |

## Lásd még

* Osztály [XmlTextWriter](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)