---
title: operator=()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli nesneye null atar.
type: docs
weight: 14
url: /tr/system/nullable/operator_equal/
---
## Nullable::operator=(std::nullptr_t) metodu

Geçerli nesneye null atar.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator=(std::nullptr_t)
```

### Dönüş Değeri

[Nullable](../) nesnesi, null-değeri temsil eder.

## Nullable::operator=(const T1\&) metodu

Nesnenin şu anda temsil edilen değerini belirtilen değerle değiştirir.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value &&!std::is_null_pointer<T1>::value, Nullable<T> &>::type System::Nullable<T>::operator=(const T1 &x)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| The | şu anki nesne tarafından temsil edilecek yeni değerin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | const T1\& | şu anki nesne tarafından temsil edilecek yeni değer |

### Dönüş Değeri

Kendisine bir referans

## Nullable::operator=(const Nullable\<T1\>\&) metodu

Nesnenin şu anda temsil edilen değerini belirtilen değerle değiştirir.

```cpp
template<typename T1> Nullable<T> & System::Nullable<T>::operator=(const Nullable<T1> &x)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| The | şu anki nesne tarafından temsil edilecek yeni değerin türü |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | const [Nullable](../)\<T1\>\& | şu anki nesne tarafından temsil edilecek yeni değer |

### Dönüş Değeri

Kendisine bir referans

## İlgili

* Sınıf [Nullable](../)
* Yapı [IsNullable](../../isnullable/)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)