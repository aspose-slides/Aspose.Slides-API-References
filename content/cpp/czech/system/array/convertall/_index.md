---
title: ConvertAll()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří nový objekt Array a naplní jej prvky specifikovaného pole převedenými na typ OutputType pomocí zadaného delegáta převodníku.
type: docs
weight: 625
url: /cs/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) metoda


Vytvoří nový objekt [Array](../) a naplní jej prvky zadaného pole převedenými na typ **OutputType** pomocí zadaného delegáta převodníku.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| InputType | Typ prvků vstupního pole |
| OutputType | Typ prvků výsledného pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Objekt [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Objekt Converter používaný k převodu každého prvku vstupního pole na ekvivalentní hodnoty typu **OutputType** |

### Návratová hodnota

Nové pole obsahující hodnoty typu **OutputType**, které jsou ekvivalentní hodnotám **input_array**.

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) metoda


Vytvoří nový objekt [Array](../) a naplní jej prvky zadaného pole převedenými na typ **OutputType** pomocí zadaného funkčního objektu převodníku.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| InputType | Typ prvků vstupního pole |
| OutputType | Typ prvků výsledného pole |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Objekt [Array](../) |
| converter | std::function\<OutputType(InputType)> | Funkční objekt používaný k převodu každého prvku vstupního pole na ekvivalentní hodnoty typu **OutputType** |

### Návratová hodnota

Nové pole obsahující hodnoty typu **OutputType**, které jsou ekvivalentní hodnotám **input_array**.

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Třída [Array](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)