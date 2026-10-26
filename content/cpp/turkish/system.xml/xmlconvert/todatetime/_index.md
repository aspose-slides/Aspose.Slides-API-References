---
title: ToDateTime()
second_title: Aspose.Slides for C++ API Referansı
description: String'i bir DateTime eşdeğerine dönüştürür.
type: docs
weight: 417
url: /tr/system.xml/xmlconvert/todatetime/
---
## XmlConvert::ToDateTime(const String\&) metodu


[String](../../../system/string/)'i bir [DateTime](../../../system/datetime/) eşdeğerine dönüştürür.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Dönüştürülecek dize. |

### Dönüş Değeri

Dizenin bir [DateTime](../../../system/datetime/) eşdeğeri.

## XmlConvert::ToDateTime(const String\&, const String\&) metodu


[String](../../../system/string/)'i bir [DateTime](../../../system/datetime/) eşdeğerine dönüştürür.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const String &format)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Dönüştürülecek dize. |
| format | const [String](../../../system/string/)\& | Dönüştürülen [DateTime](../../../system/datetime/)'ye uygulanacak biçim yapısı. Geçerli biçimler arasında \"yyyy-MM-ddTHH:mm:sszzzzzz\" ve alt kümeleri bulunur. Dize bu biçime göre doğrulanır. |

### Dönüş Değeri

Dizenin bir [DateTime](../../../system/datetime/) eşdeğeri.

## XmlConvert::ToDateTime(const String\&, const ArrayPtr\<String\>\&) metodu


[String](../../../system/string/)'i bir [DateTime](../../../system/datetime/) eşdeğerine dönüştürür.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, const ArrayPtr<String> &formats)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Dönüştürülecek dize. |
| formats | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | Dönüştürülen [DateTime](../../../system/datetime/)'ye uygulanacak biçim yapılarını içeren dizi. Geçerli biçimler arasında \"yyyy-MM-ddTHH:mm:sszzzzzz\" ve alt kümeleri bulunur. |

### Dönüş Değeri

Dizenin bir [DateTime](../../../system/datetime/) eşdeğeri.

## XmlConvert::ToDateTime(const String\&, XmlDateTimeSerializationMode) metodu


[String](../../../system/string/)'i belirtilen XmlDateTimeSerializationMode kullanarak bir [DateTime](../../../system/datetime/)'e dönüştürür.

```cpp
static DateTime System::Xml::XmlConvert::ToDateTime(const String &s, XmlDateTimeSerializationMode dateTimeOption)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | Dönüştürülecek [String](../../../system/string/) değeri. |
| dateTimeOption | [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/) | Tarihin yerel saate dönüştürülüp dönüştürülemeyeceğini veya UTC (Eşgüdümlü Evrensel Zaman) olarak korunup korunmayacağını belirten enum değerlerinden biri. |

### Dönüş Değeri

[String](../../../system/string/)'in bir [DateTime](../../../system/datetime/) eşdeğeri.

## İlgili

* Enumerasyon [XmlDateTimeSerializationMode](../../xmldatetimeserializationmode/)
* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [DateTime](../../../system/datetime/)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlConvert](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)