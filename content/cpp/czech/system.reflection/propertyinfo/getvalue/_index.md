---
title: GetValue()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá hodnotu vlastnosti z konkrétního objektu.
type: docs
weight: 1
url: /cs/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) metoda

Získá hodnotu vlastnosti z konkrétního objektu.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) pro načtení vlastnosti z. |

### Návratová hodnota

Hodnota specifikované vlastnosti pro specifikovaný objekt.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) metoda

Získá hodnotu vlastnosti z konkrétního objektu.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) pro načtení vlastnosti z. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Jedná se o volitelné indexové hodnoty pro indexované vlastnosti. Pro neindexované vlastnosti by tato hodnota měla být null. |

### Návratová hodnota

Hodnota specifikované vlastnosti pro specifikovaný objekt.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [Object](../../../system/object/)
* Třída [PropertyInfo](../)
* Jmenný prostor [System::Reflection](../../)
* Knihovna [Aspose.Slides](../../../)