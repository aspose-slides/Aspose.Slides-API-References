---
title: ConvertAll()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo oggetto Array e lo riempie con gli elementi dell'array specificato convertiti al tipo OutputType utilizzando il delegato convertitore specificato.
type: docs
weight: 625
url: /it/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) metodo

Crea un nuovo oggetto [Array](../) e lo riempie con gli elementi dell'array specificato convertiti al tipo **OutputType** usando il delegato convertitore specificato.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| InputType | The type of elements of input array |
| OutputType | The type of elements of the resulting array |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Un oggetto [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Un oggetto Converter usato per convertire ogni elemento dell'array di input in valori equivalenti del tipo **OutputType** |

### Valore restituito

Un nuovo array contenente valori del tipo **OutputType** equivalenti ai valori di **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) metodo

Crea un nuovo oggetto [Array](../) e lo riempie con gli elementi dell'array specificato convertiti al tipo **OutputType** usando l'oggetto funzione convertitore specificato.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Parametri del modello

| Parameter | Description |
| --- | --- |
| InputType | The type of elements of input array |
| OutputType | The type of elements of the resulting array |

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Un oggetto [Array](../) |
| converter | std::function\<OutputType(InputType)> | Un oggetto funzione usato per convertire ogni elemento dell'array di input in valori equivalenti del tipo **OutputType** |

### Valore restituito

Un nuovo array contenente valori del tipo **OutputType** equivalenti ai valori di **input_array**

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Classe [Array](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)