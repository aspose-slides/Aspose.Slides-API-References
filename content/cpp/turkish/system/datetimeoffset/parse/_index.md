---
title: Parse()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen dizeyi DateTimeOffset eşdeğerine dönüştürür.
type: docs
weight: 703
url: /tr/system/datetimeoffset/parse/
---
## DateTimeOffset::Parse(const String\&) metod

Belirtilen dizeyi [DateTimeOffset](../) eşdeğerine dönüştürür.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) dönüştürülecek. |

### Dönüş Değeri

[DateTimeOffset](../) **input** ile eşdeğerdir.

## DateTimeOffset::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metod

Belirtilen dizeyi [DateTimeOffset](../) nesnesine, belirtilen format sağlayıcı ve biçimlendirme stili kullanarak dönüştürür.

```cpp
static DateTimeOffset System::DateTimeOffset::Parse(const String &input, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) dönüştürülecek. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim sağlayıcı. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Tarih ve saat biçimlendirme stilleri. |

### Dönüş Değeri

[DateTimeOffset](../) **input** ile eşdeğerdir.

## Ayrıca Bakınız

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)