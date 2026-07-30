---
title: ReadBlock()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Načte z aktuálního textového čtečky určený maximální počet znaků a zapíše data do vyrovnávací paměti, počínaje zadaným indexem.
type: docs
weight: 53
url: /cs/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) metoda


Načte určený maximální počet znaků z aktuálního textového čtečky a zapíše data do vyrovnávací paměti, počínaje určeným indexem.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Vyrovnávací paměť znaků, do které se zapisují načtená data |
| index | int | Index založený na nule v **buffer**, od kterého se má začít zapisovat |
| count | int | Maximální počet znaků, které se mají načíst |

### Návratová hodnota

Skutečný počet načtených znaků

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [TextReader](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)