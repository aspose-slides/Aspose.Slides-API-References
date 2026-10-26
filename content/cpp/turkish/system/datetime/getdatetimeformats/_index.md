---
title: GetDateTimeFormats()
second_title: Aspose.Slides için C++ API Referansı
description: Her bir öğesi, mevcut nesnenin standart tarih ve saat biçim belirteçlerinden biriyle biçimlendirilmiş dize temsili olduğu dizi döndürür.
type: docs
weight: 547
url: /tr/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const yöntemi


Her bir öğesi mevcut nesnenin standart tarih ve saat biçim belirteçlerinden biriyle biçimlendirilmiş dize temsili olduğu dizi.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const yöntemi


Her bir öğesi belirtilen standart tarih ve saat biçim belirteciyle biçimlendirilmiş dize temsili olduğu dizi.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | char_t | Standart tarih ve saat biçim belirteci. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const yöntemi


Her bir öğesi standart tarih ve saat biçim belirteçlerinden biriyle ve belirtilen biçim sağlayıcı ile biçimlendirilmiş dize temsili olduğu dizi.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim sağlayıcı. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const yöntemi


Her bir öğesi belirtilen standart tarih ve saat biçim belirteci ve biçim sağlayıcı ile biçimlendirilmiş dize temsili olduğu dizi.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | char_t | Standart tarih ve saat biçim belirteci. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Biçim sağlayıcı. |

## İlgili

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [DateTime](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)