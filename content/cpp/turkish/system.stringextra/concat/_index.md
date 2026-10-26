---
title: Concat()
second_title: Aspose.Slides for C++ API Referansı
description: String dizisini birleştirir.
type: docs
weight: 1
url: /tr/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) fonksiyon

String dizisini birleştirir.

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | [Array](../../system/array/) birleştirilecek stringlerin. |

### Dönüş Değeri

Birleştirilmiş string.

## System::StringExtra::Concat(const String\&, const String\&) fonksiyon

Stringleri birleştirir.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Birleştirilecek ilk string. |
| str1 | const [String](../../system/string/)\& | Birleştirilecek ikinci string. |

### Dönüş Değeri

Birleştirilmiş parametre stringleri.

## System::StringExtra::Concat(const String\&, const String\&, const String\&) fonksiyon

Stringleri birleştirir.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Birleştirilecek ilk string. |
| str1 | const [String](../../system/string/)\& | Birleştirilecek ikinci string. |
| str2 | const [String](../../system/string/)\& | Birleştirilecek üçüncü string. |

### Dönüş Değeri

Birleştirilmiş parametre stringleri.

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) fonksiyon

Stringleri birleştirir.

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | Birleştirilecek ilk string. |
| str1 | const [String](../../system/string/)\& | Birleştirilecek ikinci string. |
| str2 | const [String](../../system/string/)\& | Birleştirilecek üçüncü string. |
| str3 | const [String](../../system/string/)\& | Birleştirilecek dördüncü string. |

### Dönüş Değeri

Birleştirilmiş parametre stringleri.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) fonksiyon

Nesneleri stringe dönüştürür ve ortaya çıkan stringleri birleştirir. [SmartPtr](../../system/smartptr/) türleri için özelleştirme.

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) dönüştürülüp birleştirilecek. |

### Dönüş Değeri

[String](../../system/string/) değeri, gönderilen tüm nesnelerin string temsillerinden birleştirilir.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) fonksiyon

Nesneleri stringe dönüştürür ve ortaya çıkan stringleri birleştirir. Aritmetik türler için özelleştirme.

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) dönüştürülüp birleştirilecek. |

### Dönüş Değeri

[String](../../system/string/) değeri, gönderilen tüm nesnelerin string temsillerinden birleştirilir.

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) fonksiyon

Nesneleri stringe dönüştürür ve ortaya çıkan stringleri birleştirir. Yapılar ve diğer değer türleri için özelleştirme.

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | [Object](../../system/object/) dönüştürülüp birleştirilecek. |

### Dönüş Değeri

[String](../../system/string/) değeri, gönderilen tüm nesnelerin string temsillerinden birleştirilir.

## İlgili

* Tip Tanımı [ArrayPtr](../../system/arrayptr/)
* Sınıf [String](../../system/string/)
* Yapı [IsSmartPtr](../../system/issmartptr/)
* Ad Alanı [System::StringExtra](../)
* Kütüphane [Aspose.Slides](../../)