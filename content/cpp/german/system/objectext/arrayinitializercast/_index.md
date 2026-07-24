---
title: ArrayInitializerCast()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert grundlegende Array-Werte (was C# implizit tut, C++ anscheinend nicht).
type: docs
weight: 209
url: /de/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) Methode


Konvertiert grundlegende Array-Werte (was C# implizit tut, C++ anscheinend nicht).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| To | Zieltyp. |
| From | Quelltypen. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| args | From ... | Werte, die konvertiert und in das Ziel-Array eingefügt werden. |

### Rückgabewert

[Array](../../array/) enthält konvertierte Kopien aller Argumente in derselben Reihenfolge.

## Siehe auch

* Klasse [ObjectExt](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)