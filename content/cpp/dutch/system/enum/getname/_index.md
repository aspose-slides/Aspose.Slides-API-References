---
title: GetName()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de naam van de enumeratie-constante die de opgegeven waarde heeft.
type: docs
weight: 40
url: /nl/system/enum/getname/
---
## Enum::GetName(T) methode


Retourneert de naam van de enumeratie-constante die de opgegeven waarde heeft.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | T | De waarde van de enum-constante waarvan de naam moet worden geretourneerd |

### Retourwaarde

De naam van de opgegeven enum-constante

## Zie ook

* Typedef [UnderlyingType](../underlyingtype/)
* Klasse [String](../../string/)
* Struct [Enum](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)