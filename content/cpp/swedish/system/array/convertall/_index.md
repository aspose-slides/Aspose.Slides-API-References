---
title: ConvertAll()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt Array-objekt och fyller det med element från den angivna arrayen som konverteras till typen OutputType med hjälp av den angivna konverteringsdelegeringen.
type: docs
weight: 625
url: /sv/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) method


Skapar ett nytt [Array](../)-objekt och fyller det med element från den angivna arrayen konverterade till typen **OutputType** med hjälp av den angivna konverteringsdelegeringen.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| InputType | Typen av element i indatararrayen |
| OutputType | Typen av element i den resulterande arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Ett [Array](../)-objekt |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Ett Converter-objekt som används för att konvertera varje element i indatararrayen till motsvarande värden av typen **OutputType** |

### Returvärde

En ny array som innehåller värden av typen **OutputType** motsvarande värdena i **input_array**

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) method


Skapar ett nytt [Array](../)-objekt och fyller det med element från den angivna arrayen konverterade till typen **OutputType** med hjälp av det angivna konverteringsfunktionsobjektet.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| InputType | Typen av element i indatararrayen |
| OutputType | Typen av element i den resulterande arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Ett [Array](../)-objekt |
| converter | std::function\<OutputType(InputType)> | Ett funktionsobjekt som används för att konvertera varje element i indatararrayen till motsvarande värden av typen **OutputType** |

### Returvärde

En ny array som innehåller värden av typen **OutputType** motsvarande värdena i **input_array**

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)