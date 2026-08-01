---
title: UnknownIsNull()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of een object van onbekend type nullptr is. Overload voor niet-scalare types.
type: docs
weight: 144
url: /nl/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) methode

Controleert of een object van onbekend type nullptr is. Overload voor niet-scalare types.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T | [Object](../../object/) om te controleren. |

### Retourwaarde

Waar als ‘obj == nullptr’ waar is, anders onwaar.

## ObjectExt::UnknownIsNull(T) methode

Controleert of een object van onbekend type nullptr is. Overload voor scalare types.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | [Object](../../object/) type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | T | [Object](../../object/) om te controleren. |

### Retourwaarde

Retourneert altijd false.

## Zie ook

* Klasse [ObjectExt](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)