---
title: ConvertAll()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy nowy obiekt Array i wypełnia go elementami określonej tablicy przekonwertowanymi na typ OutputType przy użyciu podanego delegata konwertera.
type: docs
weight: 625
url: /pl/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method

Tworzy nowy obiekt [Array](../) i wypełnia go elementami określonej tablicy przekonwertowanymi na typ **OutputType** przy użyciu podanego delegata konwertera.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| InputType | Typ elementów tablicy wejściowej |
| OutputType | Typ elementów wynikowej tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Obiekt [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Obiekt Converter używany do konwersji każdego elementu tablicy wejściowej na równoważne wartości typu **OutputType** |

### Wartość zwracana

Nową tablicę zawierającą wartości typu **OutputType** równoważne wartościom **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method

Tworzy nowy obiekt [Array](../) i wypełnia go elementami określonej tablicy przekonwertowanymi na typ **OutputType** przy użyciu podanego obiektu funkcyjnego konwertera.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| InputType | Typ elementów tablicy wejściowej |
| OutputType | Typ elementów wynikowej tablicy |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Obiekt [Array](../) |
| converter | std::function\<OutputType(InputType)> | Obiekt funkcyjny używany do konwersji każdego elementu tablicy wejściowej na równoważne wartości typu **OutputType** |

### Wartość zwracana

Nową tablicę zawierającą wartości typu **OutputType** równoważne wartościom **input_array**

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)