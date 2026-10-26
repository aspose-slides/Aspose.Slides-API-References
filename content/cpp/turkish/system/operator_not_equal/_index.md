---
title: operator!=()
second_title: Aspose.Slides için C++ API Referansı
description: 
type: docs
weight: 2055
url: /tr/system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) function




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```
## System::operator!=(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```
## System::operator!=(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```
## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) function


Belirtilen [Nullable](../nullable/) nesnesinin null olmayan bir değeri temsil edip etmediğini belirler.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | std::nullptr_t | Test edilecek bir [Nullable](../nullable/) nesnesine sabit referans |

### Dönüş Değeri

Belirtilen nesne null olmayan bir değeri temsil ediyorsa doğru, aksi takdirde yanlış

## System::operator!=(const T1\&, const Nullable\<T2\>\&) function


Bu değerlere [operator!=()](./) uygulanarak, belirtilen değerin belirtilen [Nullable](../nullable/) nesnesi tarafından temsil edilen değere eşit olmaması belirlenir.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | İlk karşılaştırılan değerin türü |
| T2 | İkinci karşılaştırılan değeri temsil eden [Nullable](../nullable/) nesnesinin temel türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| some | const T1\& | İlk karşılaştırma için kullanılacak değere sabit referans |
| other | const [Nullable](../nullable/)\<T2\>\& | İkinci karşılaştırma için kullanılacak değeri temsil eden [Nullable](../nullable/) nesnesine sabit referans |

### Dönüş Değeri

Karşılaştırılan değerler eşit değilse doğru, aksi takdirde – yanlış

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) function


İki akıllı göstergenin eşit olmama karşılaştırması.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | İlk göstergecinin işaret ettiği tip. |
| Y | İkinci göstergecinin işaret ettiği tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Karşılaştırılacak ilk göstergeç. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Karşılaştırılacak ikinci göstergeç. |

### Dönüş Değeri

Göstergeçler eşleşiyorsa yanlış, aksi takdirde doğru.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) function


Akıllı göstergenin null olup olmadığını denetler.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | Göstergecin işaret ettiği tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Denenecek göstergeç. |

### Dönüş Değeri

Göstergeç null ise yanlış, aksi takdirde doğru.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) function


Akıllı göstergenin null olup olmadığını denetler.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | Göstergecin işaret ettiği tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | std::nullptr_t | Denenecek göstergeç. |

### Dönüş Değeri

Göstergeç null ise yanlış, aksi takdirde doğru.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) function


Akıllı göstergenin basit (C) göstergeciyle eşitsizlik karşılaştırması.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | Akıllı göstergeç tipi. |
| Y | Basit göstergeç tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | Karşılaştırılacak akıllı göstergeç (sol). |
| y | const Y * | Karşılaştırılacak göstergeç (sağ). |

### Dönüş Değeri

Göstergeçler eşleşiyorsa yanlış, aksi takdirde doğru.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) function


Akıllı göstergenin basit (C) göstergeciyle eşitlik karşılaştırması.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| X | Basit göstergeç tipi. |
| Y | Akıllı göstergeç tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const X * | Karşılaştırılacak göstergeç (sağ). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Karşılaştırılacak akıllı göstergeç (sol). |

### Dönüş Değeri

Göstergeçler eşleşiyorsa yanlış, aksi takdirde doğru.

## System::operator!=(Chars\&, const String\&) function


[String](../string/) karşılaştırması.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Chars | [String](../string/) literal tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | Chars\& | Karşılaştırılacak [String](../string/) literal. |
| right | const [String](../string/)\& | Karşılaştırılacak [String](../string/). |

### Dönüş Değeri

Dizeler eşleşiyorsa false, aksi takdirde true.

## System::operator!=(T\&, const String\&) function


[String](../string/) karşılaştırması.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [String](../string/) göstergeç tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | T\& | Karşılaştırılacak [String](../string/) göstergeç. |
| right | const [String](../string/)\& | Karşılaştırılacak [String](../string/). |

### Dönüş Değeri

Dizeler eşleşiyorsa false, aksi takdirde true.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) function


[Object](../object/) ve string karşılaştırması.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | Stringe dönüştürülüp karşılaştırılacak [Object](../object/). |
| right | const [String](../string/)\& | Karşılaştırılacak [String](../string/). |

### Dönüş Değeri

Nesnenin string temsili stringe eşitse false, aksi takdirde true.

## System::operator!=(std::nullptr_t, const String\&) function


Stringin null olup olmadığını denetler.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| str | std::nullptr_t | Denenecek [String](../string/). |

### Dönüş Değeri

String null ise false, aksi takdirde true.

## System::operator!=(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) function


Mevcut ve belirtilen nesneler tarafından temsil edilen URI'ların eşit olmaması belirlenir.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Karşılaştırılacak ilk [Uri](../uri/) nesnesi |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | Karşılaştırılacak ikinci [Uri](../uri/) nesnesi |

### Dönüş Değeri

URI'lar eşit değilse doğru, aksi takdirde – false

## See Also

* Tip Tanımı [SharedPtr](../sharedptr/)
* Sınıf [ArraySegment](../arraysegment/)
* Sınıf [DateTime](../datetime/)
* Sınıf [DateTimeOffset](../datetimeoffset/)
* Sınıf [Nullable](../nullable/)
* Sınıf [SmartPtr](../smartptr/)
* Sınıf [Object](../object/)
* Sınıf [String](../string/)
* Sınıf [TimeSpan](../timespan/)
* Sınıf [Uri](../uri/)
* Yapı [IsNullable](../isnullable/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)