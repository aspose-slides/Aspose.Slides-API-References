---
title: Read()
second_title: Aspose.Slides pro C++ – reference API
description: Přečte jeden znak ze streamu.
type: docs
weight: 40
url: /cs/system.io/stringreader/read/
---
## StringReader::Read() metoda


Přečte jeden znak ze streamu.

```cpp
virtual int System::IO::StringReader::Read() override
```


### Návratová hodnota

Přečtený znak nebo -1, pokud nebyl žádný znak přečten


## StringReader::Read(ArrayPtr\<char_t\>, int, int) metoda


Přečte zadaný počet znaků ze streamu do zadaného pole znaků počínaje zadanou pozicí.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Pole znaků, do kterého se zapíší znaky přečtené ze streamu |
| index | int | Index založený na nule v **buffer**, od kterého se má začít zapisovat |
| count | int | Počet znaků, které se mají přečíst ze streamu |

### Návratová hodnota

Počet znaků přečtených ze streamu

## Viz také

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [StringReader](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)