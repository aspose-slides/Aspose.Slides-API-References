---
title: GetValue()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar egenskapens värde från ett specifikt objekt.
type: docs
weight: 1
url: /sv/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) metod


Hämtar egenskapsvärde från ett specifikt objekt.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) för att läsa egenskap från. |

### Returvärde

Värdet på angiven egenskap för angivet objekt.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) metod


Hämtar egenskapsvärde från ett specifikt objekt.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) för att läsa egenskap från. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Detta är valfria indexvärden för indexerade egenskaper. För icke-indexerade egenskaper bör detta värde vara null. |

### Returvärde

Värdet på angiven egenskap för angivet objekt.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Object](../../../system/object/)
* Klass [PropertyInfo](../)
* Namnrymd [System::Reflection](../../)
* Bibliotek [Aspose.Slides](../../../)