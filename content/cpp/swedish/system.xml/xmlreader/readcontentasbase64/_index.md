---
title: ReadContentAsBase64()
second_title: Aspose.Slides för C++ API-referens
description: Läser innehållet och returnerar de Base64-avkodade binära bytena.
type: docs
weight: 755
url: /sv/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metod


Läser innehållet och returnerar de Base64-avkodade binära bytena.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufferten som resultattexten ska kopieras till. Detta värde kan inte vara **nullptr**. |
| index | **int32_t** | Offseten i bufferten där kopieringen av resultatet ska börja. |
| count | **int32_t** | Det maximala antalet byte som får kopieras till bufferten. Det faktiska antalet kopierade byte returneras från denna metod. |

### Returvärde

Antalet byte som skrevs till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)