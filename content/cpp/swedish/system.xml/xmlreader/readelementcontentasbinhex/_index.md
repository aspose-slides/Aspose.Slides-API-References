---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides för C++ API-referens
description: Läser elementet och avkodar BinHex-innehållet.
type: docs
weight: 794
url: /sv/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod


Läser elementet och avkodar **BinHex**-innehållet.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Den buffert som den resulterande texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Offseten i bufferten där resultatet ska börja kopieras. |
| count | **int32_t** | Det maximala antalet byte som ska kopieras till bufferten. Det faktiska antalet kopierade byte returneras från denna metod. |

### Returvärde

Antalet byte som skrevs till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)