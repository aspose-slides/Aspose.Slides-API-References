---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides för C++ API-referens
description: Läser elementet och avkodar Base64-innehållet.
type: docs
weight: 586
url: /sv/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod

Läser elementet och avkodar Base64-innehållet.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten som texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Förskjutningen i bufferten där kopieringen av resultatet ska börja. |
| count | **int32_t** | Det maximala antalet bytes att kopiera till bufferten. Det faktiska antalet kopierade bytes returneras av den här metoden. |

### Returvärde

Antalet bytes som skrevs till bufferten.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlValidatingReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)