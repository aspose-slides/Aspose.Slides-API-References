---
title: ConvertAll()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří seznam prvků převedených na jiný typ.
type: docs
weight: 352
url: /cs/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) metoda

Vytvoří seznam prvků převedených na jiný typ.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| OutputType | Typ prvku výstupního seznamu. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Převodník používaný pro převod položek. |

### Návratová hodnota

Nově vytvořený seznam převedených prvků.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Třída [List](../)
* Jmenný prostor [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)