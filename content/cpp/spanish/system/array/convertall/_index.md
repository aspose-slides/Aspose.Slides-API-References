---
title: ConvertAll()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye un nuevo objeto Array y lo llena con los elementos del array especificado convertidos al tipo OutputType usando el delegado convertidor especificado.
type: docs
weight: 625
url: /es/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method

Construye un nuevo objeto [Array](../) y lo llena con los elementos del array especificado convertidos al tipo **OutputType** usando el delegado convertidor especificado.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| InputType | El tipo de los elementos del array de entrada |
| OutputType | El tipo de los elementos del array resultante |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Un objeto [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Un objeto Converter usado para convertir cada elemento del array de entrada a valores equivalentes del tipo **OutputType** |

### Valor devuelto

Un nuevo array que contiene valores del tipo **OutputType** equivalentes a los valores de **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method

Construye un nuevo objeto [Array](../) y lo llena con los elementos del array especificado convertidos al tipo **OutputType** usando el objeto función convertidor especificado.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Parámetros de plantilla

| Parámetro | Descripción |
| --- | --- |
| InputType | El tipo de los elementos del array de entrada |
| OutputType | El tipo de los elementos del array resultante |

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Un objeto [Array](../) |
| converter | std::function\<OutputType(InputType)> | Un objeto función usado para convertir cada elemento del array de entrada a valores equivalentes del tipo **OutputType** |

### Valor devuelto

Un nuevo array que contiene valores del tipo **OutputType** equivalentes a los valores de **input_array**

## Ver también

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Clase [Array](../)
* Espacio de nombres [System](../../)
* Biblioteca [Aspose.Slides](../../../)