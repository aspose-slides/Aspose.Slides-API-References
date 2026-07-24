---
title: operator+=()
second_title: Aspose.Slides C++ için API Referansı
description: Geçerli nesneyi sıfırlar, böylece bir null değeri temsil eder.
type: docs
weight: 235
url: /tr/system/nullable/operator_plus_equal/
---
## Nullable::operator+=(std::nullptr_t) yöntemi


Geçerli nesneyi sıfırlar, böylece bir null değeri temsil eder.

```cpp
Nullable<T> System::Nullable<T>::operator+=(std::nullptr_t)
```


### Dönüş Değeri

Kendisinin bir kopyası

## Nullable::operator+=(const T1\&) yöntemi


[operator+=()](./) öğesini geçerli nesnenin temsil ettiği değere, belirtilen değeri sağ taraf argümanı olarak kullanarak uygular.

```cpp
template<typename T1> std::enable_if<!IsNullable<T1>::value, Nullable<T>>::type System::Nullable<T>::operator+=(const T1 &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | [operator+=()](./) öğesinin sağ taraf değeri olarak kullanılan değerin türü |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const T1\& | Geçerli nesnenin temsil ettiği değere uygulanan [operator+=()](./)'nin sağ taraf değeri olarak kullanılan değere sabit bir referans. |

### Dönüş Değeri

Kendisine bir referans

## Nullable::operator+=(const Nullable\<T1\>\&) yöntemi


[operator+=()](./) öğesini geçerli nesnenin temsil ettiği değere, belirtilen [Nullable](../) nesnesinin temsil ettiği değeri sağ taraf argümanı olarak kullanarak uygular.

```cpp
template<typename T1> Nullable<T> System::Nullable<T>::operator+=(const Nullable<T1> &other)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T1 | [operator+=()](./) öğesinin sağ taraf argümanı olarak kullanılan değeri temsil eden [Nullable](../) nesnesinin temel türü |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | Geçerli nesnenin temsil ettiği değere uygulanan [operator+=()](./)'nin sağ taraf argümanı olarak kullanılan değeri temsil eden [Nullable](../) nesnesine sabit bir referans. |

### Dönüş Değeri

Kendisine bir referans

## İlgili

* Sınıf [Nullable](../)
* Yapı [IsNullable](../../isnullable/)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)