---
title: SpecifyKind()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen DateTime nesnesiyle aynı sayıda tik'i temsil eden yeni bir DateTime nesnesi oluşturur ve argüman kind tarafından belirtilen şekilde yerel zaman, UTC zamanı veya hiçbirini temsil eder.
type: docs
weight: 833
url: /tr/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) yöntemi

Belirtilen [DateTime](../) nesnesiyle aynı sayıda tik'i temsil eden yeni bir [DateTime](../) nesnesi oluşturur ve **kind** argümanıyla belirtilen yerel zaman, UTC zamanı veya hiçbirini temsil eder.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DateTime](../) | [DateTime](../) nesnesinden tik sayısını kopyalamak için kullanılan nesne |
| kind | [DateTimeKind](../../datetimekind/) | Yeni nesnenin yerel zamanı, UTC zamanını veya hiçbirini temsil edip etmeyeceğini belirtir. |

### Dönüş Değeri

**value** ve **kind** tarafından belirtilen DateTimeKind değeriyle aynı sayıda tik'i temsil eden yeni bir [DateTime](../) nesnesi.

## Ayrıca Bakınız

* Enum [DateTimeKind](../../datetimekind/)
* Class [DateTime](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)