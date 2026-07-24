---
title: Parse()
second_title: Aspose.Slides for C++ API Referansı
description: Ondalık bir sayının dize temsili, Decimal sınıfının eşdeğer bir örneğine dönüştürülür.
type: docs
weight: 469
url: /tr/system/decimal/parse/
---
## Decimal::Parse(const String\&) yöntemi


Bir ondalık sayının dize temsili, [Decimal](../) sınıfının eşdeğer bir örneğine dönüştürülür.

```cpp
static Decimal System::Decimal::Parse(const String &s)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Bir sayının dize temsili |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen değere eşdeğer bir [Decimal](../) sınıfının yeni örneği.

## Decimal::Parse(const String\&, Globalization::NumberStyles) yöntemi


Belirtilen stil kullanılarak bir ondalık sayının dize temsili, [Decimal](../) sınıfının eşdeğer bir örneğine dönüştürülür.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülmek üzere bir ondalık değerin dize temsili |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | **s** hakkında, **s** içinde bulunabilecek stil öğeleri hakkında veya **s**'nin bir [Decimal](../) nesnesine dönüştürülmesi hakkında ek bilgi sağlayan enum değerlerinin bit düzeyi birleşimi |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen değere eşdeğer bir [Decimal](../) sınıfının yeni örneği

## Decimal::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) yöntemi


Belirtilen format sağlayıcı kullanılarak bir ondalık sayının dize temsili, [Decimal](../) sınıfının eşdeğer bir örneğine dönüştürülür.

```cpp
static Decimal System::Decimal::Parse(const String &s, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülmek üzere bir ondalık değerin dize temsili |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format sağlayıcı |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen değere eşdeğer bir [Decimal](../) sınıfının yeni örneği

## Decimal::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) yöntemi


Belirtilen stil ve format sağlayıcı kullanılarak bir ondalık sayının dize temsili, [Decimal](../) sınıfının eşdeğer bir örneğine dönüştürülür.

```cpp
static Decimal System::Decimal::Parse(const String &s, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| s | const [String](../../string/)\& | Dönüştürülmek üzere bir ondalık değerin dize temsili |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | **s** hakkında, **s** içinde bulunabilecek stil öğeleri hakkında veya **s**'nin bir [Decimal](../) nesnesine dönüştürülmesi hakkında ek bilgi sağlayan enum değerlerinin bit düzeyi birleşimi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format sağlayıcı |

### Dönüş Değeri

Belirtilen dize tarafından temsil edilen değere eşdeğer bir [Decimal](../) sınıfının yeni örneği

## Ayrıca Bakınız

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Decimal](../)
* Sınıf [String](../../string/)
* Sınıf [IFormatProvider](../../iformatprovider/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)