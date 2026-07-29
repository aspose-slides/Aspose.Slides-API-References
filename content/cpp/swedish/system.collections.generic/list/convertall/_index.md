---
title: ConvertAll()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en lista med element konverterade till en annan typ.
type: docs
weight: 352
url: /sv/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) metod


Skapar en lista med element konverterade till en annan typ.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| OutputType | Typ av element i utdata-listan. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Konverterare som används för konvertering av objekt. |

### Returvärde

En ny skapad lista med konverterade element.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Class [List](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)