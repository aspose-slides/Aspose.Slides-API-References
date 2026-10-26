---
title: ReadValueChunk()
second_title: Aspose.Slides pro C++ API Reference
description: Čte velké proudy textu vložené do XML dokumentu.
type: docs
weight: 807
url: /cs/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) method

Čte velké proudy textu vložené do XML dokumentu.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Pole znaků sloužící jako vyrovnávací paměť, do které se zapisují textové obsahy. Tato hodnota nesmí být **nullptr**. |
| index | **int32_t** | Posun v rámci vyrovnávací paměti, kde může [XmlReader](../) začít kopírovat výsledky. |
| count | **int32_t** | Maximum počtu znaků, které mají být zkopírovány do vyrovnávací paměti. Skutečný počet zkopírovaných znaků je vrácen tímto metodou. |

### Návratová hodnota

Počet znaků načtených do vyrovnávací paměti. Hodnota nula je vrácena, když už není žádný textový obsah.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)