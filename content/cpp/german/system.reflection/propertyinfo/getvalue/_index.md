---
title: GetValue()
second_title: Aspose.Slides für C++ API Referenz
description: Liest den Eigenschaftswert aus einem bestimmten Objekt.
type: docs
weight: 1
url: /de/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) Methode

Liest den Eigenschaftswert aus einem bestimmten Objekt.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) zum Auslesen der Eigenschaft. |

### Rückgabewert

Wert der angegebenen Eigenschaft für das angegebene Objekt.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) Methode

Liest den Eigenschaftswert aus einem bestimmten Objekt.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) zum Auslesen der Eigenschaft. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Dies sind optionale Indexwerte für indizierte Eigenschaften. Für nicht indizierte Eigenschaften sollte dieser Wert null sein. |

### Rückgabewert

Wert der angegebenen Eigenschaft für das angegebene Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [PropertyInfo](../)
* Namensraum [System::Reflection](../../)
* Library [Aspose.Slides](../../../)