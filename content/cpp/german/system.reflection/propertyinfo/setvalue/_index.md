---
title: SetValue()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt den Eigenschaftswert auf ein bestimmtes Objekt.
type: docs
weight: 14
url: /de/system.reflection/propertyinfo/setvalue/
---
## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>) Methode

Setzt den Eigenschaftswert auf ein bestimmtes Objekt.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) zum Schreiben der Eigenschaft. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Wert der Eigenschaft, die gesetzt werden soll. |

## PropertyInfo::SetValue(System::SharedPtr\<System::Object\>, System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) Methode

Setzt den Eigenschaftswert auf ein bestimmtes Objekt.

```cpp
void System::Reflection::PropertyInfo::SetValue(System::SharedPtr<System::Object> obj, System::SharedPtr<System::Object> value, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) zum Schreiben der Eigenschaft. |
| indexer | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Dies sind optionale Indexwerte für indizierte Eigenschaften. Für nicht indizierte Eigenschaften sollte dieser Wert null sein. |
| value | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Wert der Eigenschaft, die gesetzt werden soll. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [Object](../../../system/object/)
* Klasse [PropertyInfo](../)
* Namensraum [System::Reflection](../../)
* Bibliothek [Aspose.Slides](../../../)