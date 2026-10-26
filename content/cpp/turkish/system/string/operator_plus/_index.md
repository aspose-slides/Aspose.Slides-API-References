---
title: operator+()
second_title: Aspose.Slides for C++ API Referansı
description: Dize birleştirme operatörü.
type: docs
weight: 274
url: /tr/system/string/operator_plus/
---
## String::operator+(const String\&) const metod


[String](../) birleştirme operatörü.

```cpp
String System::String::operator+(const String &str) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) mevcut olanın sonuna eklemek için. |

### Dönüş Değeri

Birleştirilmiş dize.

## String::operator+(const T\&) const metod


[String](../) dize sabiti veya karakter dizi işaretçisiyle birleştirme.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Dize sabiti veya karakter dizi işaretçisi biçimlerinden biri. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg | const T\& | Geçerli dizeyle birleştirilecek varlık. |

### Dönüş Değeri

Birleştirilmiş dize.

## String::operator+(char_t) const metod


Dize sonuna karakter ekler.

```cpp
String System::String::operator+(char_t x) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | char_t | Eklemek için karakter. |

### Dönüş Değeri

[String](../) birleştirme sonucu.

## String::operator+(int) const metod


Dize sonuna tamsayı değerinin dize temsilini ekler.

```cpp
String System::String::operator+(int i) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | int | Dizeye dönüştürülüp eklenecek tamsayı değeri. |

### Dönüş Değeri

[String](../) birleştirme sonucu.

## String::operator+(uint32_t) const metod


Dize sonuna işaretsiz tamsayı değerinin dize temsilini ekler.

```cpp
String System::String::operator+(uint32_t i) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| i | **uint32_t** | Dizeye dönüştürülüp eklenecek değer. |

### Dönüş Değeri

[String](../) birleştirme sonucu.

## String::operator+(double) const metod


Dize sonuna kayan nokta değerinin dize temsilini ekler.

```cpp
String System::String::operator+(double d) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| d | **double** | Dizeye dönüştürülüp eklenecek değer. |

### Dönüş Değeri

[String](../) birleştirme sonucu.

## String::operator+(int64_t) const metod


Dize sonuna tamsayı değerinin dize temsilini ekler.

```cpp
String System::String::operator+(int64_t v) const
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| v | **int64_t** | Dizeye dönüştürülüp eklenmek üzere değer. |

### Dönüş Değeri

[String](../) birleştirme sonucu.

## String::operator+(const T\&) const metod


Referans tip nesnenin dize temsilini dize sonuna ekler.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | işaretçi tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) [ToString()](../tostring/) çağrısı kullanılarak dizeye dönüştürülüp mevcut dizeye eklemek için. |

### Dönüş Değeri

[String](../) birleştirme sonucu.

## String::operator+(const T\&) const metod


Değer tipi nesnenin dize temsilini dize sonuna ekler.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [ToString()](../tostring/) üzerine çağrı yapılacak değer tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) [ToString()](../tostring/) çağrısı kullanılarak dizeye dönüştürülüp mevcut dizeye eklemek için. |

### Dönüş Değeri

[String](../) birleştirme sonucu.

## String::operator+(T) const metod


Boolean değerinin dize temsilini dize sonuna ekler.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Dizeyle birleştirilecek değer tipi. Bool olmalıdır. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) değerini dizeye dönüştürüp eklemek için. |

### Dönüş Değeri

[String](../) birleştirme sonucu.

## Bkz

* Sınıf [String](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)