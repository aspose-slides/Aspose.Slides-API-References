---
title: ParseExact()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen biçim, biçim sağlayıcı ve biçimlendirme stili kullanılarak belirtilen dizeyi DateTimeOffset nesnesine dönüştürür.
type: docs
weight: 716
url: /tr/system/datetimeoffset/parseexact/
---
## DateTimeOffset::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metodu

Belirtilen biçim, biçim sağlayıcı ve biçimlendirme stili kullanılarak belirtilen dizeyi [DateTimeOffset](../) nesnesine dönüştürür.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) dönüştürmek için. |
| format | const [String](../../string/)\& | Biçim dizesi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim sağlayıcı. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Tarih ve saat biçimlendirme stilleri. |

### Dönüş Değeri

[DateTimeOffset](../) **input** ile eşdeğer olan.

## DateTimeOffset::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) metodu

Belirtilen biçimler, biçim sağlayıcı ve biçimlendirme stili kullanılarak belirtilen dizeyi [DateTimeOffset](../) nesnesine dönüştürür.

```cpp
static DateTimeOffset System::DateTimeOffset::ParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) dönüştürmek için. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) biçim dizesi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim sağlayıcı. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Tarih ve saat biçimlendirme stilleri. |

### Dönüş Değeri

[DateTimeOffset](../) **input** ile eşdeğer olan.

## İlgili

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTimeOffset](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)