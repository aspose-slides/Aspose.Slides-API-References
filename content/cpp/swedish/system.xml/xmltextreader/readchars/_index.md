---
title: ReadChars()
second_title: Aspose.Slides för C++ API-referens
description: Läser textinnehållet i ett element till en teckenbuffert. Denna metod är avsedd att läsa stora strömmar av inbäddad text genom att anropa den successivt.
type: docs
weight: 755
url: /sv/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metod

Läser textinnehållet i ett element till en teckenbuffert. Denna metod är avsedd att läsa stora strömmar av inbäddad text genom att anropa den successivt.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Den array av tecken som fungerar som den buffert dit textinnehållet skrivs. |
| index | **int32_t** | Positionen i **buffer** där metoden kan börja skriva textinnehåll. |
| count | **int32_t** | Antalet tecken som ska skrivas in i **buffer**. |

### Returvärde

Antalet tecken som lästs. Detta kan vara 0 om läsaren inte är placerad på ett element eller om det inte finns mer textinnehåll att returnera i det aktuella sammanhanget.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [XmlTextReader](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)