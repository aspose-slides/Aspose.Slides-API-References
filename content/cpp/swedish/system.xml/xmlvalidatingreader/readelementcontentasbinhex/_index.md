---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides för C++ API-referens
description: Läser elementet och avkodar BinHex-innehållet.
type: docs
weight: 612
url: /sv/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod


Läser elementet och avkodar BinHex-innehållet.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten som den resulterande texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Förskjutningen i bufferten där kopieringen av resultatet ska börja. |
| count | **int32_t** | Det maximala antalet bytes som ska kopieras till bufferten. Det faktiska antalet kopierade bytes returneras av den här metoden. |

### Returvärde

Antalet bytes som har skrivits till bufferten.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlValidatingReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)