---
title: ReadContentAsBinHex()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet och returnerar de BinHex avkodade binära bytarna.
type: docs
weight: 781
url: /sv/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod


Läser innehållet och returnerar de **BinHex** avkodade binära bytarna.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten som texten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Offseten i bufferten där resultatet ska börja kopieras. |
| count | **int32_t** | Det maximala antalet byte som ska kopieras till bufferten. Det faktiska antalet kopierade byte returneras från denna metod. |

### Returvärde

Antalet byte som skrivits till bufferten.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)