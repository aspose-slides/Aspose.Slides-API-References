---
title: ObjectToUnknown()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert Object naar een onbekend type, waarbij zowel smart pointer-typen als verpakte waardesituaties worden afgehandeld.
type: docs
weight: 131
url: /nl/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) methode

Converteert [Object](../../object/) naar een onbekend type, waarbij zowel smart pointer-typen als verpakte waardesituaties worden afgehandeld.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type om [Object](../../object/) naar te converteren. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) om te converteren. |

### Retourwaarde

Ofwel een uitpakbare waarde of een geconverteerde pointer.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) methode

Converteert [Object](../../object/) naar een onbekend type, waarbij zowel smart pointer-typen als verpakte waardesituaties worden afgehandeld.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Type om [Object](../../object/) naar te converteren. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) om te converteren. |

### Retourwaarde

Ofwel een uitpakbare waarde of een geconverteerde pointer.

## Zie ook

* Klasse [SmartPtr](../../smartptr/)
* Klasse [Object](../../object/)
* Klasse [ObjectExt](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)