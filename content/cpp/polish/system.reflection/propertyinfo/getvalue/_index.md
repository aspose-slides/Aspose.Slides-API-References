---
title: GetValue()
second_title: Aspose.Slides dla C++ Referencja API
description: Pobiera wartość właściwości z określonego obiektu.
type: docs
weight: 1
url: /pl/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) method

Pobiera wartość właściwości z określonego obiektu.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) z którego odczytać właściwość. |

### Wartość zwracana

Wartość określonej właściwości dla określonego obiektu.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) method

Pobiera wartość właściwości z określonego obiektu.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) z którego odczytać właściwość. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Są to opcjonalne wartości indeksu dla właściwości indeksowanych. Dla właściwości nieindeksowanych ta wartość powinna być null. |

### Wartość zwracana

Wartość określonej właściwości dla określonego obiektu.

## Zobacz również

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [Object](../../../system/object/)
* Klasa [PropertyInfo](../)
* Przestrzeń nazw [System::Reflection](../../)
* Biblioteka [Aspose.Slides](../../../)