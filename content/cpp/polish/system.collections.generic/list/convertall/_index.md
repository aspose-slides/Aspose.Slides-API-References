---
title: ConvertAll()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy listę elementów przekonwertowanych na inny typ.
type: docs
weight: 352
url: /pl/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) method


Tworzy listę elementów przekonwertowanych na inny typ.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| OutputType | Typ elementu listy wyjściowej. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Konwerter używany do konwersji elementów. |

### Wartość zwracana

Nowa lista przekonwertowanych elementów.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Klasa [List](../)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)