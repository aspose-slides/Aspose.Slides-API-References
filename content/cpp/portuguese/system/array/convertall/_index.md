---
title: ConvertAll()
second_title: Referência da API Aspose.Slides para C++
description: Constrói um novo objeto Array e o preenche com os elementos da matriz especificada convertidos para o tipo OutputType usando o delegate conversor especificado.
type: docs
weight: 625
url: /pt/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method

Constrói um novo objeto [Array](../) e preenche-o com os elementos da matriz especificada convertidos para o tipo **OutputType** usando o delegate conversor especificado.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| InputType | O tipo dos elementos da matriz de entrada |
| OutputType | O tipo dos elementos da matriz resultante |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Um objeto [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Um objeto Converter usado para converter cada elemento da matriz de entrada em valores equivalentes do tipo **OutputType** |

### Valor de Retorno

Uma nova matriz contendo valores do tipo **OutputType** equivalentes aos valores de **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method

Constrói um novo objeto [Array](../) e preenche-o com os elementos da matriz especificada convertidos para o tipo **OutputType** usando o objeto de função conversor especificado.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| InputType | O tipo dos elementos da matriz de entrada |
| OutputType | O tipo dos elementos da matriz resultante |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Um objeto [Array](../) |
| converter | std::function\<OutputType(InputType)> | Um objeto de função usado para converter cada elemento da matriz de entrada em valores equivalentes do tipo **OutputType** |

### Valor de Retorno

Uma nova matriz contendo valores do tipo **OutputType** equivalentes aos valores de **input_array**

## Veja Também

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)