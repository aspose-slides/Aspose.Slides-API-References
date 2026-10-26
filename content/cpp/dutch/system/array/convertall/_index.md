---
title: ConvertAll()
second_title: Aspose.Slides voor C++ API Referentie
description: Construeert een nieuw Array-object en vult het met elementen van de opgegeven array die zijn geconverteerd naar type OutputType met behulp van de opgegeven converter-delegate.
type: docs
weight: 625
url: /nl/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method

Construeert een nieuw [Array](../) object en vult het met elementen van de opgegeven array die zijn geconverteerd naar type **OutputType** met behulp van de opgegeven converter-delegate.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| InputType | Het type van de elementen van de invoerarray |
| OutputType | Het type van de elementen van de resulterende array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Een [Array](../) object |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Een Converter object dat wordt gebruikt om elk element van de invoerarray te converteren naar equivalente waarden van type **OutputType** |

### Retourwaarde

Een nieuwe array die waarden van type **OutputType** bevat die equivalent zijn aan de waarden van **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method

Construeert een nieuw [Array](../) object en vult het met elementen van de opgegeven array die zijn geconverteerd naar type **OutputType** met behulp van het opgegeven converter-functieobject.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| InputType | Het type van de elementen van de invoerarray |
| OutputType | Het type van de elementen van de resulterende array |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Een [Array](../) object |
| converter | std::function\<OutputType(InputType)> | Een functieobject dat wordt gebruikt om elk element van de invoerarray te converteren naar equivalente waarden van type **OutputType** |

### Retourwaarde

Een nieuwe array die waarden van type **OutputType** bevat die equivalent zijn aan de waarden van **input_array**

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Klasse [Array](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)