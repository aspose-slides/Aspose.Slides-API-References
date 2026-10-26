---
title: TryParseExact()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizgiyi, belirtilen biçimler, biçim sağlayıcı ve biçimlendirme stilini kullanarak DateTimeOffset nesnesine dönüştürmeyi dener.
type: docs
weight: 742
url: /tr/system/datetimeoffset/tryparseexact/
---
## DateTimeOffset::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method

Belirtilen dizeyi, belirtilen biçimler, biçim sağlayıcı ve biçimlendirme stilini kullanarak [DateTimeOffset](../) nesnesine dönüştürmeyi dener.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) dönüştürmek için. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Biçim dizgelerinin dizileri. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim sağlayıcı. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Tarih ve saat biçimlendirme stilleri. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) **input** ile eşdeğer olan. |

### Return Value

true if the **input** converted successfully, otherwise - false.

## DateTimeOffset::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTimeOffset\&) method

Belirtilen dizeyi, belirtilen biçim, biçim sağlayıcı ve biçimlendirme stilini kullanarak [DateTimeOffset](../) nesnesine dönüştürmeyi dener.

```cpp
static bool System::DateTimeOffset::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTimeOffset &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | [String](../../string/) dönüştürmek için. |
| format | const [String](../../string/)\& | Biçim dizgesi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim sağlayıcı. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Tarih ve saat biçimlendirme stilleri. |
| result | [DateTimeOffset](../)\& | [DateTimeOffset](../) **input** ile eşdeğer olan. |

### Return Value

true if the **input** converted successfully, otherwise - false.

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTimeOffset](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)