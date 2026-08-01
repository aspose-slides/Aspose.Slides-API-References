---
title: SetValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de eigenschapswaarde in op een specifiek object.
type: docs
weight: 14
url: /nl/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) method

Stelt de eigenschapswaarde in op een specifiek object.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) om de eigenschap naar te schrijven. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Waarde van de in te stellen eigenschap. |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) method

Stelt de eigenschapswaarde in op een specifiek object.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) om de eigenschap naar te schrijven. |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Dit zijn optionele indexwaarden voor geïndiceerde eigenschappen. Voor niet-geïndiceerde eigenschappen moet deze waarde null zijn. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Waarde van de in te stellen eigenschap. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [PropertyInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)