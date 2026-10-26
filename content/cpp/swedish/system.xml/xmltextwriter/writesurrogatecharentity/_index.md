---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides för C++ API-referens
description: Skapar och skriver surrogatteckenenheten för surrogatteckenparet.
type: docs
weight: 391
url: /sv/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) metod

Genererar och skriver surrogatteckenenheten för surrogatteckenparet.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lowChar | char16_t | Den låga surrogaten. Detta måste vara ett värde mellan **0xDC00** och **0xDFFF**. |
| highChar | char16_t | Den höga surrogaten. Detta måste vara ett värde mellan **0xD800** och **0xDBFF**. |

## Se även

* Klass [XmlTextWriter](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)