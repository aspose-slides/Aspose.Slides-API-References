---
title: ReadBase64()
second_title: Aspose.Slides för C++ API-referens
description: Avkodar Base64 och returnerar de avkodade binära bytena.
type: docs
weight: 768
url: /sv/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Avkodar Base64 och returnerar de avkodade binära bytena.

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen av tecken som fungerar som bufferten som textinnehållet skrivs till. |
| offset | **int32_t** | Det nollbaserade indexet i arrayen som anger var metoden kan börja skriva till bufferten. |
| len | **int32_t** | Antalet byte som ska skrivas till bufferten. |

### Returvärde

Antalet byte som har skrivits till bufferten.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)