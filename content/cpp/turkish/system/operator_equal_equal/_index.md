---
title: operator==()
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 2042
url: /tr/system/operator_equal_equal/
---
## System::operator==(ArraySegment\<T\>, ArraySegment\<T\>) fonksiyonu




```cpp
template<typename T> bool System::operator==(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator==(std::nullptr_t, DateTime) fonksiyonu




```cpp
constexpr bool System::operator==(std::nullptr_t, DateTime)
```

## System::operator==(std::nullptr_t, const DateTimeOffset\&) fonksiyonu




```cpp
constexpr bool System::operator==(std::nullptr_t, const DateTimeOffset &)
```

## System::operator==(std::nullptr_t, const Nullable\<T\>\&) fonksiyonu


Belirtilen [Nullable](../nullable/) nesnesinin değerin null olmasına eşit olup olmadığını belirler.

```cpp
template<typename T> bool System::operator==(std::nullptr_t, const Nullable<T> &other)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | std::nullptr_t | Test edilmek üzere bir [Nullable](../nullable/) nesnesine sabit referans |

### Dönüş Değeri

Belirtilen nesnenin null değeri temsil etmesi durumunda doğru, aksi takdirde yanlış

## System::operator==(const T1\&, const Nullable\<T2\>\&) fonksiyonu


Belirtilen değerin, belirtilen [Nullable](../nullable/) nesnesi tarafından temsil edilen değerle eşit olup olmadığını, bu değerlere [operator==()](./) uygulanarak belirler.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator==(const T1 &some, const Nullable<T2> &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | İlk karşılaştırılan değer türü |
| T2 | İkinci karşılaştırılan değeri temsil eden [Nullable](../nullable/) nesnesinin temel türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| some | const T1\& | İlk karşılaştırılan değer olarak kullanılacak değere sabit referans |
| other | const [Nullable](../nullable/)\<T2\>\& | Temsil ettiği değer ikinci karşılaştırılan değer olarak kullanılacak [Nullable](../nullable/) nesnesine sabit referans |

### Dönüş Değeri

Karşılaştırılan değerler eşitse doğru, aksi takdirde - yanlış

## System::operator==(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) fonksiyonu


İki akıllı işaretçiyi eşitlik açısından karşılaştırır.

```cpp
template<class X,class Y> bool System::operator==(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | İlk işaretçinin işaret ettiği tip. |
| Y | İkinci işaretçinin işaret ettiği tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Karşılaştırılacak ilk işaretçi. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Karşılaştırılacak ikinci işaretçi. |

### Dönüş Değeri

İşaretçiler eşleşiyorsa doğru, aksi takdirde yanlış.

## System::operator==(std::nullptr_t, SmartPtr\<X\> const\&) fonksiyonu


Akıllı işaretçinin null olup olmadığını denetler.

```cpp
template<class X> bool System::operator==(std::nullptr_t, SmartPtr<X> const &x)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | İşaretçinin işaret ettiği tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | std::nullptr_t | Denetlenecek işaretçi. |

### Dönüş Değeri

İşaretçi null ise doğru, aksi takdirde yanlış.

## System::operator==(const SmartPtr\<X\>\&, const Y *) fonksiyonu


Akıllı işaretçiyi basit (C) işaretçiyle eşitlik açısından karşılaştırır.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const SmartPtr<X> &x, const Y *y)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | Akıllı işaretçinin tipi. |
| Y | Basit işaretçinin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Sol tarafta karşılaştırılacak akıllı işaretçi. |
| y | const Y * | Sağ tarafta karşılaştırılacak işaretçi. |

### Dönüş Değeri

İşaretçiler eşleşiyorsa doğru, aksi takdirde yanlış.

## System::operator==(const X *, const SmartPtr\<Y\>\&) fonksiyonu


Akıllı işaretçiyi basit (C) işaretçiyle eşitlik açısından karşılaştırır.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator==(const X *x, const SmartPtr<Y> &y)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | Basit işaretçinin tipi. |
| Y | Akıllı işaretçinin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const X * | Sağ tarafta karşılaştırılacak işaretçi. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Sol tarafta karşılaştırılacak akıllı işaretçi. |

### Dönüş Değeri

İşaretçiler eşleşiyorsa doğru, aksi takdirde yanlış.

## System::operator==(T const\&, std::nullptr_t) fonksiyonu


Değer tipi nesnesinin (çevrilmiş C# yapısı vb.) null olup olmadığını denetler.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(T const &x, std::nullptr_t)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değer tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | T const\& | Denetlenecek [Object](../object/). |

### Dönüş Değeri

Nesne null ise doğru, aksi takdirde yanlış.

## System::operator==(std::nullptr_t, T const\&) fonksiyonu


Değer tipi nesnesinin (çevrilmiş C# yapısı vb.) null olup olmadığını denetler.

```cpp
template<class T> std::enable_if<!std::is_scalar<T>::value &&!std::is_pointer<T>::value &&!std::is_array<T>::value &&detail::has_method_is_null<T>::value, bool>::type System::operator==(std::nullptr_t, T const &x)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değer tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | std::nullptr_t | Denetlenecek [Object](../object/). |

### Dönüş Değeri

Nesne null ise doğru, aksi takdirde yanlış.

## System::operator==(Chars\&, const String\&) fonksiyonu


[String](../string/) karşılaştırması.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator==(Chars &left, const String &right)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Chars | [String](../string/) sabit değer tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | Chars\& | Karşılaştırılacak [String](../string/) sabit değeri. |
| right | const [String](../string/)\& | Karşılaştırılacak [String](../string/). |

### Dönüş Değeri

Dizeler eşleşiyorsa true, aksi takdirde false.

## System::operator==(T\&, const String\&) fonksiyonu


[String](../string/) karşılaştırması.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator==(T &left, const String &right)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [String](../string/) işaretçi tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | T\& | Karşılaştırılacak [String](../string/) işaretçi. |
| right | const [String](../string/)\& | Karşılaştırılacak [String](../string/). |

### Dönüş Değeri

Dizeler eşleşiyorsa true, aksi takdirde false.

## System::operator==(const SharedPtr\<Object\>\&, const String\&) fonksiyonu


[Object](../object/) ve dize karşılaştırması.

```cpp
bool System::operator==(const SharedPtr<Object> &left, const String &right)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) nesnesini dizeye dönüştürüp karşılaştırmak için. |
| right | const [String](../string/)\& | Karşılaştırılacak [String](../string/). |

### Dönüş Değeri

Nesnenin dize temsili dizeye eşitse true, aksi takdirde false.

## System::operator==(std::nullptr_t, const String\&) fonksiyonu


Dizenin null olup olmadığını denetler.

```cpp
bool System::operator==(std::nullptr_t, const String &str)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | std::nullptr_t | Denetlenecek [String](../string/). |

### Dönüş Değeri

Dize null ise true, aksi takdirde false.

## System::operator==(std::nullptr_t, TimeSpan) fonksiyonu




```cpp
constexpr bool System::operator==(std::nullptr_t, TimeSpan)
```

## System::operator==(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) fonksiyonu


Mevcut ve belirtilen nesneler tarafından temsil edilen URI'ların eşit olup olmadığını belirler.

```cpp
bool System::operator==(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Karşılaştırılacak ilk [Uri](../uri/) nesnesi |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Karşılaştırılacak ikinci [Uri](../uri/) nesnesi |

### Dönüş Değeri

URI'lar eşitse true, aksi takdirde - false

## Bkz

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)