---
title: GetDescription()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de naam van de enumeratieconstante die de opgegeven waarde heeft.
type: docs
weight: 53
url: /nl/system/enum/getdescription/
---
## Enum::GetDescription(T) methode

Retourneert de naam van de enumeratieconstante die de opgegeven waarde heeft.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T | De waarde van de enumconstante waarvan de naam moet worden geretourneerd |

### Retourwaarde

De naam van de opgegeven enumconstante

## Zie ook

* Typedef [UnderlyingType](../underlyingtype/)
* Klasse [String](../../string/)
* Struct [Enum](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)