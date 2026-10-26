---
title: Is()
second_title: Aspose.Slides for C++ API Referansı
description: 'is' operatörünün çevirisini uygular. Kutulanabilir (değer) tipler için özelleştirme.
type: docs
weight: 92
url: /tr/system/objectext/is/
---
## ObjectExt::Is(const T\&) method

‘is’ operatörünün çevirisini uygular. Tam olarak kutulanabilir (değer) tipler için özelleştirme.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) ‘is’ operatörünü test etmek için. Yoksayılır. |

## Dönüş Değeri

Always true

## ObjectExt::Is(const U\&) method

‘is’ operatörünün çevirisini uygular. ‘final’ sınıflar için optimize edilmiş işaretçi tipleri için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |
| U | Test edilen tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const U\&) method

‘is’ operatörünün çevirisini uygular. İşaretçi tipleri için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |
| U | Test edilen tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const Object\&) method

‘is’ operatörünün çevirisini uygular. Değer tipleri için özelleştirme.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const Object\&) method

‘is’ operatörünün çevirisini uygular. Dönüştürülemez tipler için özelleştirme.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

Always returns false as types are unconvertible.

## ObjectExt::Is(const SmartPtr\<U\>\&) method

‘is’ operatörünün çevirisini uygular. İşaretçi tipleri için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) method

‘is’ operatörünün çevirisini uygular. İstisna sarmalayıcı tipleri için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<Object\>\&) method

‘is’ operatörünün çevirisini uygular. Nullable tipleri için özelleştirme.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<Object\>\&) method

‘is’ operatörünün çevirisini uygular. ‘==’ operatörü tanımlı kutulanabilir tipler için özelleştirme.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<Object\>\&) method

‘is’ operatörünün çevirisini uygular. ‘==’ operatörü tanımlanmamış kutulanabilir tipler için özelleştirme.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<V\>\&) method

‘is’ operatörünün çevirisini uygular. Arayüzlere kutulanmış değer tipleri için özelleştirme.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |
| V | İşaret edilen nesnenin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<U\>\&) method

‘is’ operatörünün çevirisini uygular. Enum tipleri için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |
| U | İşaret edilen nesnenin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const WeakPtr\<U\>\&) method

‘is’ operatörünün çevirisini uygular. Enum tipleri ile zayıf işaretçiler için özelleştirme.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |
| U | İşaret edilen nesnenin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) ‘is’ operatörünü test etmek için. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const Nullable\<U\>\&) method

‘is’ operatörünün çevirisini uygular. [Nullable](../../nullable/) tipi için özelleştirme.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) tipi. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const char16_t *) method

‘is’ operatörünün çevirisini uygular. Dizgi sabiti için özelleştirme.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) sabiti. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## ObjectExt::Is(int32_t) method

‘is’ operatörünün çevirisini uygular. Tam sayı sabiti için özelleştirme.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Hedef tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **int32_t** | tam sayı sabiti. |

## Dönüş Değeri

True if 'is' returns true, false otherwise.

## İlgili

* Sınıf [ObjectExt](../)
* Sınıf [Object](../../object/)
* Sınıf [SmartPtr](../../smartptr/)
* Sınıf [ExceptionWrapper](../../exceptionwrapper/)
* Sınıf [WeakPtr](../../weakptr/)
* Sınıf [Nullable](../../nullable/)
* Yapı [IsBoxable](../../isboxable/)
* Yapı [IsSmartPtr](../../issmartptr/)
* Yapı [IsExceptionWrapper](../../isexceptionwrapper/)
* Yapı [IsNullable](../../isnullable/)
* İsim alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)