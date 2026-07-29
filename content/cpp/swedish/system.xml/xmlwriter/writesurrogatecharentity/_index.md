---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides för C++ API-referens
description: När den åsidosätts i en avledd klass genereras och skrivs surrogatteckenentiteten för surrogatteckenparet.
type: docs
weight: 261
url: /sv/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) metod

När den åsidosätts i en avledd klass genereras och skrivs en surrogat-teckenentitet för surrogat-teckenparet.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lowChar | char16_t | Den låga surrogaten. Detta måste vara ett värde mellan 0xDC00 och 0xDFFF. |
| highChar | char16_t | Den höga surrogaten. Detta måste vara ett värde mellan 0xD800 och 0xDBFF. |

## Se också

* Klass [XmlWriter](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)