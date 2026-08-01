---
title: UnknownToObject()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert een onbekend type naar Object, waarbij zowel smart pointer-type als waardetype-situaties worden afgehandeld.
type: docs
weight: 118
url: /nl/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) methode

Converteert een onbekend type naar [Object](../../object/), waarbij zowel smart pointer-type als waardetype-situaties worden afgehandeld.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type om naar [Object](../../object/) te converteren. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T | [Object](../../object/) om te converteren. |

### Retourwaarde

Smart pointer naar [Object](../../object/) die of een geconverteerde pointer of een verpakte waarde is.

## ObjectExt::UnknownToObject(const T\&) methode

Converteert een onbekend type naar [Object](../../object/), waarbij zowel smart pointer-type als waardetype-situaties worden afgehandeld.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type om naar [Object](../../object/) te converteren. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) om te converteren. |

### Retourwaarde

Smart pointer naar [Object](../../object/) die of een geconverteerde pointer of een verpakte waarde is.

## Zie ook

* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)