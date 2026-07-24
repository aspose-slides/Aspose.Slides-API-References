---
title: HasFlag()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen enum değerinin bit dizimi temsili içinde belirtilen bitlerin ayarlanıp ayarlanmadığını belirler.
type: docs
weight: 14
url: /tr/system/enum/hasflag/
---
## Enum::HasFlag(E, E) yöntemi

Belirtilen enum değerinin bit dizimi temsilinde belirtilen bitlerin ayarlanıp ayarlanmadığını belirler.

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | E | Test edilecek enum değeri |
| mask | E | value'ın bitlerini kontrol etmek için maske |

### Dönüş Değeri

**mask** içinde ayarlanmış bitler **value** içinde de ayarlandığında True, aksi takdirde false

## Ayrıca Bak

* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)