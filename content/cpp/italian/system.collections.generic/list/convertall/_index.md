---
title: ConvertAll()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un elenco di elementi convertiti in un tipo diverso.
type: docs
weight: 352
url: /it/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) metodo


Crea un elenco di elementi convertiti in un tipo diverso.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| OutputType | Tipo di elemento dell'elenco di output. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Converter da utilizzare per la conversione degli elementi. |

### Valore restituito

Un elenco appena creato di elementi convertiti.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Classe [List](../)
* Spazio dei nomi [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)