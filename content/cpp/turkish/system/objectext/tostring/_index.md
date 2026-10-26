---
title: ToString()
second_title: Aspose.Slides için C++ API Referansı
description: Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.
type: docs
weight: 27
url: /tr/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) yöntem

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) dizgiye dönüştürülecek literal. |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## ObjectExt::ToString(const Nullable\<T\>\&) yönt

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Nullable](../../nullable/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) dizgiye dönüştürülecek nesne. |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## ObjectExt::ToString(const T\&) yönt

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Enum](../../enum/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) dizgiye dönüştürülecek değer. |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## ObjectExt::ToString(const T\&) yönt

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Akıllı işaretçi türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) dizgiye dönüştürülecek değer. |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## ObjectExt::ToString(T\&) yönt

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Akıllı işaretçi türü veya [ExceptionWrapper](../../exceptionwrapper/). |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\& | Dizgiye dönüştürülecek akıllı işaretçi veya [ExceptionWrapper](../../exceptionwrapper/). |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## ObjectExt::ToString(T\&) yönt

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Skaler tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\& | Dizgiye dönüştürülecek skaler değer. |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## ObjectExt::ToString(T\&&) yönt

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Skaler tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\&& | Dizgiye dönüştürülecek skaler değer. |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## ObjectExt::ToString(T\&) yönt

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Yapı türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\& | Dizgiye dönüştürülecek yapı değeri. |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## ObjectExt::ToString(const T\&) yöntem

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Yapı türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | Dizgiye dönüştürülecek yapı değeri. |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## ObjectExt::ToString(T\&&) yönt

Herhangi bir C++ türünde çalışacak C# ToString yönteminin yerine geçer.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Skaler tür. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | T\&& | Dizgiye dönüştürülecek skaler değer. |

### Dönüş Değeri

[String](../../string/) **obj**'ın temsili.

## Ayrıca Bakınız

* Sınıf [String](../../string/)
* Sınıf [ObjectExt](../)
* Sınıf [Nullable](../../nullable/)
* Yapı [IsSmartPtr](../../issmartptr/)
* Yapı [IsExceptionWrapper](../../isexceptionwrapper/)
* Yapı [IsNullable](../../isnullable/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)