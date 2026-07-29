---
title: ArrayInitializerCast()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar grundläggande arrayvärden (vilket C# gör implicit men C++ uppenbarligen inte gör).
type: docs
weight: 209
url: /sv/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) metod

Konverterar grundläggande arrayvärden (vilket C# gör implicit men C++ uppenbarligen inte gör).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| To | Måltyp. |
| From | Källtyper. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | From ... | Värden att konvertera och lägga till i målarrayen. |

### Returvärde

[Array](../../array/) innehåller konverterade kopior av alla argument i samma ordning.

## Se också

* Klass [ObjectExt](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)