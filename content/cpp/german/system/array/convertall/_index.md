---
title: ConvertAll()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Array-Objekt und füllt es mit Elementen des angegebenen Arrays, die mithilfe des angegebenen Converter-Delegaten in den Typ OutputType konvertiert wurden.
type: docs
weight: 625
url: /de/system/array/convertall/
---
## Array::ConvertAll(ArrayPtr\<InputType\>, Converter\<InputType, OutputType\>) Methode


Erstellt ein neues [Array](../) Objekt und füllt es mit Elementen des angegebenen Arrays, die mithilfe des angegebenen Converter-Delegaten in den Typ **OutputType** konvertiert wurden.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, Converter<InputType, OutputType> converter)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| InputType | Der Typ der Elemente des Eingabearrays |
| OutputType | Der Typ der Elemente des resultierenden Arrays |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Ein [Array](../) Objekt |
| converter | [Converter](../../converter/)\<InputType, OutputType\> | Ein Converter-Objekt, das verwendet wird, um jedes Element des Eingabearrays in äquivalente Werte des Typs **OutputType** zu konvertieren |

### Rückgabewert

Ein neues Array, das Werte des Typs **OutputType** enthält, die den Werten von **input_array** entsprechen

## Array::ConvertAll(ArrayPtr\<InputType\>, std::function\<OutputType(InputType)>) Methode


Erstellt ein neues [Array](../) Objekt und füllt es mit Elementen des angegebenen Arrays, die mithilfe des angegebenen Converter-Funktionsobjekts in den Typ **OutputType** konvertiert wurden.

```cpp
template<typename InputType,typename OutputType> static ArrayPtr<OutputType> System::Array<T>::ConvertAll(ArrayPtr<InputType> input_array, std::function<OutputType(InputType)> converter)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| InputType | Der Typ der Elemente des Eingabearrays |
| OutputType | Der Typ der Elemente des resultierenden Arrays |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| input_array | [ArrayPtr](../../arrayptr/)\<InputType\> | Ein [Array](../) Objekt |
| converter | std::function\<OutputType(InputType)> | Ein Funktionsobjekt, das verwendet wird, um jedes Element des Eingabearrays in äquivalente Werte des Typs **OutputType** zu konvertieren |

### Rückgabewert

Ein neues Array, das Werte des Typs **OutputType** enthält, die den Werten von **input_array** entsprechen

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Converter](../../converter/)
* Klasse [Array](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)