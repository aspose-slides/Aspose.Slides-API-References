---
title: TryParse()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen, bir sayının dize temsilini içeren dizeyi eşdeğer Decimal değerine dönüştürür.
type: docs
weight: 482
url: /tr/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) metot


Belirtilen, bir sayının dize temsilini içeren dizeyi eşdeğer [Decimal](../) değerine dönüştürür.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| result | [Decimal](../)\& | [Decimal](../) değişkenine dönüşüm sonucunun yerleştirildiği referans |

### Dönüş Değeri

True eğer dönüşüm başarılıysa, aksi takdirinde - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) metot


Belirtilen, bir sayının dize temsilini içeren dizeyi, sağlanan biçimlendirme bilgileri ve sayı stili kullanılarak eşdeğer [Decimal](../) değerine dönüştürür.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../string/)\& | Dönüştürülecek dize |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | İzin verilen sayı temsili stilini belirten NumberStyles enum değerlerinin bit düzeyinde bir kombinasyonu |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Dize biçim bilgilerini içeren bir nesneye işaretçi |
| result | [Decimal](../)\& | Çıkış argümanı; dönüşüm sonucunu içerir |

### Dönüş Değeri

True eğer dönüşüm başarılıysa, aksi takdirinde - false

## Ayrıca Bakınız

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [String](../../string/)
* Sınıf [Decimal](../)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)