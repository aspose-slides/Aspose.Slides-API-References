---
title: ReadChars()
second_title: Aspose.Slides pro C++ API Reference
description: Čte textový obsah prvku do znakové vyrovnávací paměti. Tato metoda je navržena pro čtení velkých toků vloženého textu postupným voláním.
type: docs
weight: 755
url: /cs/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metoda

Čte textový obsah prvku do znakové vyrovnávací paměti. Tato metoda je navržena pro čtení velkých toků vloženého textu postupným voláním.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Pole znaků, které slouží jako buffer, do kterého jsou zapisovány textové obsahy. |
| index | **int32_t** | Pozice v rámci **buffer**, kde může metoda začít zapisovat textové obsahy. |
| count | **int32_t** | Počet znaků, které mají být zapsány do **buffer**. |

### Návratová hodnota

Počet přečtených znaků. Může být 0, pokud čtečka není umístěna na prvek nebo pokud v aktuálním kontextu již není žádný textový obsah k vrácení.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)