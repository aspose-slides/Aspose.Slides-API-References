---
title: TryParse()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen sayının dize temsili içeren dizeyi, eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.
type: docs
weight: 14
url: /tr/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) metod


Belirtilen dizeyi, sayının dize temsili içeren, eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| result | **float**\& | Dönüşüm sonucunun konulacağı tek duyarlıklı kayan nokta değişkenine referans. |

### Dönüş Değeri

Dönüşüm başarılıysa true, aksi takdirde - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) metod


Belirtilen dizeyi, sayının dize temsili içeren, sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak eşdeğer tek duyarlıklı kayan nokta değerine dönüştürür.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum değerlerinin bit düzeyinde birleştirilmesi; sayının dize temsili için izin verilen stili belirtir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren nesneye işaretçi. |
| result | **float**\& | Dönüşüm sonucunun konulacağı tek duyarlıklı kayan nokta değişkenine referans. |

### Dönüş Değeri

Dönüşüm başarılıysa true, aksi takdirde - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) metod




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) metod




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) metod




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## İlgili

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Sınıf [CultureInfo](../../../system.globalization/cultureinfo/)
* Sınıf [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* İsim Uzayı [System](../../)
* Library [Aspose.Slides](../../../)