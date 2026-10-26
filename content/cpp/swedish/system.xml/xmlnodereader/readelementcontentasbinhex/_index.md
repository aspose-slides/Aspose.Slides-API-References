---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides för C++ API-referens
description: Läser elementet och avkodar BinHex-innehållet.
type: docs
weight: 482
url: /sv/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod

Läser elementet och avkodar BinHex-innehållet.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten som texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Förskjutning i bufferten där resultatet ska börja kopieras. |
| count | **int32_t** | Det maximala antalet byte som ska kopieras till bufferten. Det faktiska antalet kopierade byte returneras från den här metoden. |

### Returvärde

Antalet byte som skrevs till bufferten.

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlNodeReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)