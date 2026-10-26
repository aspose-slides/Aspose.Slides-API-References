---
title: ToDateTimeOffset()
second_title: Aspose.Slides for C++ API Referansı
description: Sağlanan String'i bir DateTimeOffset eşdeğerine dönüştürür.
type: docs
weight: 430
url: /tr/system.xml/xmlconvert/todatetimeoffset/
---
## XmlConvert::ToDateTimeOffset(const String\&) metod

Sağlanan [String](../../../system/string/) değerini bir [DateTimeOffset](../../../system/datetimeoffset/) eşdeğerine dönüştürür.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Dönüştürülecek dize. Dize, XML dateTime tipinin W3C Önerisi'nin bir alt kümesine uymalıdır. Daha fazla bilgi için XML [Schema](../../../system.xml.schema/) spesifikasyonunun [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) bölümüne bakın. |

### Dönüş Değeri

Sağlanan dizenin [DateTimeOffset](../../../system/datetimeoffset/) eşdeğeri.

## XmlConvert::ToDateTimeOffset(const String\&, const String\&) metod

Sağlanan [String](../../../system/string/) değerini bir [DateTimeOffset](../../../system/datetimeoffset/) eşdeğerine dönüştürür.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const String &format)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Dönüştürülecek dize. |
| format | const [String](../../../system/string/)\& | Dizenin **s** dönüştürüldüğü biçim. Biçim parametresi, XML dateTime tipinin W3C Önerisi'nin herhangi bir alt kümesi olabilir. Daha fazla bilgi için XML [Schema](../../../system.xml.schema/) spesifikasyonunun [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) bölümüne bakın. Dize **s**, bu biçime göre doğrulanır. |

### Dönüş Değeri

Sağlanan dizenin [DateTimeOffset](../../../system/datetimeoffset/) eşdeğeri.

## XmlConvert::ToDateTimeOffset(const String\&, const ArrayPtr\<String\>\&) metod

Sağlanan [String](../../../system/string/) değerini bir [DateTimeOffset](../../../system/datetimeoffset/) eşdeğerine dönüştürür.

```cpp
static DateTimeOffset System::Xml::XmlConvert::ToDateTimeOffset(const String &s, const ArrayPtr<String> &formats)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Dönüştürülecek dize. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Dize **s** nin dönüştürülebileceği biçimlerin bir dizisi. **formats** içindeki her biçim, XML dateTime tipinin W3C Önerisi'nin herhangi bir alt kümesi olabilir. Daha fazla bilgi için XML [Schema](../../../system.xml.schema/) spesifikasyonunun [dateTime](https://www.w3.org/TR/xmlschema-2/#dateTime) bölümüne bakın. Dize **s**, bu biçimlerden biriyle doğrulanır. |

### Dönüş Değeri

Sağlanan dizenin [DateTimeOffset](../../../system/datetimeoffset/) eşdeğeri.

## İlgili

* Tip tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [DateTimeOffset](../../../system/datetimeoffset/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlConvert](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)