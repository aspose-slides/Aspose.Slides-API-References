---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen sayının dize temsilini içeren dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.
type: docs
weight: 14
url: /tr/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) metodu


Belirtilen sayının dize temsilini içeren dizeyi eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| result | **double**\& | Dönüştürmenin sonucu yerleştirilen çift duyarlıklı kayan nokta değişkenine referans. |

### Dönüş Değeri

Dönüşüm başarılıysa true, aksi takdirde false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) metodu


Belirtilen sayının dize temsilini içeren dizeyi, sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak eşdeğer çift duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde bir kombinasyonu; sayının dize temsilinin izin verilen stilini belirtir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçimlendirme bilgilerini içeren bir nesneye işaretçi. |
| result | **double**\& | Dönüştürmenin sonucu yerleştirilen çift duyarlıklı kayan nokta değişkenine referans. |

### Dönüş Değeri

Dönüşüm başarılıysa true, aksi takdirde false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) metodu




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) metodu




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) metodu




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Diğer Bağlantılar

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)