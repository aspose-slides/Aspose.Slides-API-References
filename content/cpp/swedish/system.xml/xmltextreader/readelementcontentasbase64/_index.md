---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides för C++ API-referens
description: Läser elementet och avkodar Base64-innehållet.
type: docs
weight: 651
url: /sv/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

Läser elementet och avkodar Base64-innehållet.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Den buffert som den resulterande texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Offseten i bufferten där resultatet ska börja kopieras. |
| count | **int32_t** | Det maximala antalet byte som ska kopieras till bufferten. Det faktiska antalet kopierade byte returneras från den här metoden. |

### Returvärde

Antalet byte som skrivs till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)