---
title: Equals()
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 14
url: /tr/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) metot




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) metot

C# [Object.Equals](../../object/equals/) çağrılarının C++'ta herhangi bir türde çalışmasını sağlayan bir ikame. Akıllı gösterici türleri için aşırı yük.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Dönüş Değeri

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(T, const T2\&) metot

C# [Object.Equals](../../object/equals/) çağrılarının C++'ta herhangi bir türde çalışmasını sağlayan bir ikame. Yapı türleri için aşırı yük.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | First object. |
| another | const T2\& | Second object. |

### Dönüş Değeri

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(const T\&, const T2\&) metot

C# [Object.Equals](../../object/equals/) çağrılarının C++'ta herhangi bir türde çalışmasını sağlayan bir ikame. Skaler türler için aşırı yük.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Dönüş Değeri

True if objects are considered equal, false otherwise.

## ObjectExt::Equals(const char_t(&), String) metot

C# [Object.Equals](../../object/equals/) çağrılarının C++'ta herhangi bir türde çalışmasını sağlayan bir ikame. Dize sabitiyle dize karşılaştırması için aşırı yük.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| N | [String](../../string/) sabit boyutu. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) sabiti. |
| another | [String](../../string/) | [String](../../string/). |

### Dönüş Değeri

True if strings match, false otherwise.

## ObjectExt::Equals(const float\&, const float\&) metot

IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const **float**\& | LHS floating point değeri. |
| another | const **float**\& | RHS floating point değeri. |

### Dönüş Değeri

True if **obj** and **another** are both NaN or equal, false otherwise.

## ObjectExt::Equals(const double\&, const double\&) metot

IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const **double**\& | LHS floating point değeri. |
| another | const **double**\& | RHS floating point değeri. |

### Dönüş Değeri

True if **obj** and **another** are both NaN or equal, false otherwise.

## İlgili

* Sınıf [ObjectExt](../)
* Sınıf [String](../../string/)
* Yapı [IsExceptionWrapper](../../isexceptionwrapper/)
* Yapı [IsSmartPtr](../../issmartptr/)
* İsim Uzayı [System](../../)
* Kütüphane [Aspose.Slides](../../../)