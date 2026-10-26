---
title: GetValue()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de eigenschapswaarde op van een specifiek object.
type: docs
weight: 1
url: /nl/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) methode

Haalt de eigenschapswaarde op van een specifiek object.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) om de eigenschap te lezen van. |

### Retourwaarde

Waarde van de gespecificeerde eigenschap voor het opgegeven object.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) methode

Haalt de eigenschapswaarde op van een specifiek object.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) om de eigenschap te lezen van. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Dit zijn optionele indexwaarden voor geïndexeerde eigenschappen. Voor niet-geïndexeerde eigenschappen moet deze waarde null zijn. |

### Retourwaarde

Waarde van de gespecificeerde eigenschap voor het opgegeven object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [PropertyInfo](../)
* Naamruimte [System::Reflection](../../)
* Bibliotheek [Aspose.Slides](../../../)