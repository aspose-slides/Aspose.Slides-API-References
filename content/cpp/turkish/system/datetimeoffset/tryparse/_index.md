---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizeyi DateTimeOffset nesnesine dönüştürmeye çalışır.
type: docs
weight: 729
url: /tr/system/datetimeoffset/tryparse/
---
## DateTimeOffset::TryParse(const String\&, DateTimeOffset\&) yöntemi

Belirtilen dizeyi [DateTimeOffset](../) nesnesine dönüştürmeye çalışır.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, DateTimeOffset &result)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) dönüştürmek için. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) **input** ile eşdeğer olan. |

### Dönüş Değeri

Eğer **input** başarıyla dönüştürüldüyse true, aksi takdirde false.

## DateTimeOffset::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) yöntemi

Belirtilen dizeyi, belirtilen biçim sağlayıcı ve biçimlendirme stili kullanarak [DateTimeOffset](../) nesnesine dönüştürmeye çalışır.

```cpp
static bool System::DateTimeOffset::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) dönüştürmek için. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim sağlayıcı. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Tarih ve saat biçimlendirme stilleri. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) **input** ile eşdeğer olan. |

### Dönüş Değeri

Eğer **input** başarıyla dönüştürüldüyse true, aksi takdirde false.

## İlgili

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTimeOffset](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)