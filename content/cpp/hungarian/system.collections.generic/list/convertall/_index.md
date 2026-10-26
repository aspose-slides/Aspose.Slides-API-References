---
title: ConvertAll()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy listát az elemekből, amelyek más típusra konvertálva vannak.
type: docs
weight: 352
url: /hu/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter<T, OutputType>) metódus

Létrehoz egy listát az elemekből, amelyek más típusra konvertálva vannak.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| OutputType | A kimeneti listaelem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)<T, OutputType> | Az elemek konvertálásához használandó konverter. |

### Visszatérési érték

Az átalakított elemekből álló újonnan létrehozott lista.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Osztály [List](../)
* Névtere [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)