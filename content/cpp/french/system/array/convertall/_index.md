---
title: ConvertAll()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un nouvel objet Array et le remplit avec les éléments du tableau spécifié convertis au type OutputType à l'aide du délégué convertisseur spécifié.
type: docs
weight: 625
url: /fr/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method

Construit un nouvel objet [Array](../) et le remplit avec les éléments du tableau spécifié convertis au type **OutputType** à l'aide du délégué convertisseur spécifié.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Template parameters

| Paramètre | Description |
| --- | --- |
| InputType | Le type des éléments du tableau d'entrée |
| OutputType | Le type des éléments du tableau résultant |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Un objet [Array](../) |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Un objet Converter utilisé pour convertir chaque élément du tableau d'entrée en valeurs équivalentes du type **OutputType** |

### Return Value

Un nouveau tableau contenant des valeurs du type **OutputType** équivalentes aux valeurs de **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method

Construit un nouvel objet [Array](../) et le remplit avec les éléments du tableau spécifié convertis au type **OutputType** à l'aide de l'objet fonction convertisseur spécifié.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Template parameters

| Paramètre | Description |
| --- | --- |
| InputType | Le type des éléments du tableau d'entrée |
| OutputType | Le type des éléments du tableau résultant |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Un objet [Array](../) |
| converter | std::function\<OutputType(InputType)> | Un objet fonction utilisé pour convertir chaque élément du tableau d'entrée en valeurs équivalentes du type **OutputType** |

### Return Value

Un nouveau tableau contenant des valeurs du type **OutputType** équivalentes aux valeurs de **input_array**

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)