---
title: ConvertAll()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy új Array objektumot, és feltölti a megadott tömb elemeivel, amelyeket a megadott converter delegát segítségével OutputType típusra konvertál.
type: docs
weight: 625
url: /hu/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) metódus

Létrehoz egy új [Array](../) objektumot, és feltölti a megadott tömb elemeivel, amelyek a megadott konverter delegált segítségével **OutputType** típusra konvertálva vannak.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| InputType | The type of elements of input array |
| OutputType | The type of elements of the resulting array |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | An [Array](../) object |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | A Converter object used to convert each element of the input array to equivalent values of **OutputType** type |

### Visszatérési érték

Egy új tömb, amely **OutputType** típusú értékeket tartalmaz, amelyek ekvivalensek a **input_array** értékeivel

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) metódus

Létrehoz egy új [Array](../) objektumot, és feltölti a megadott tömb elemeivel, amelyek a megadott konverter függvényobjektum segítségével **OutputType** típusra konvertálva vannak.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| InputType | The type of elements of input array |
| OutputType | The type of elements of the resulting array |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | An [Array](../) object |
| converter | std::function\<OutputType(InputType)> | A function object used to convert each element of the input array to equivalent values of **OutputType** type |

### Visszatérési érték

Egy új tömb, amely **OutputType** típusú értékeket tartalmaz, amelyek ekvivalensek a **input_array** értékeivel

## Lásd még

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Osztály [Array](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)