---
title: MakeArray()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir Array nesnesi oluşturan, belirtilen başlatma listesindeki öğelerle dolduran ve Array nesnesine işaret eden bir akıllı gösterici döndüren bir fabrika işlevi.
type: docs
weight: 2029
url: /tr/system/makearray/
---
## System::MakeArray(std::initializer_list\<T\>) fonksiyon


Yeni bir [Array](../array/) nesnesi oluşturan bir fabrika işlevi, belirtilen başlatma listesinde bulunan öğelerle doldurur ve [Array](../array/) nesnesine işaret eden bir akıllı gösterici döndürür.

```cpp
template<typename T> ArrayPtr<T> System::MakeArray(std::initializer_list<T> init)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun oluşturduğu [Array](../array/) nesnesinin öğelerinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| init | std::initializer_list\<T\> | Diziyi dolduracak öğeleri içeren başlatma listesi |

### Dönüş Değeri

Oluşturulan [Array](../array/) nesnesine işaret eden bir akıllı gösterici

## System::MakeArray(Args\&&...) fonksiyon


Belirtilen argümanları yapıcıya geçiren yeni bir [Array](../array/) nesnesi oluşturan bir fabrika işlevi.

```cpp
template<class T,class...> ArrayPtr<T> System::MakeArray(Args &&... args)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun oluşturduğu [Array](../array/) nesnesinin öğelerinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| args | Args\&&... | Oluşturulan [Array](../array/) nesnesinin yapıcısına geçirilen argümanlar |

### Dönüş Değeri

Oluşturulan [Array](../array/) nesnesine işaret eden bir akıllı gösterici

## System::MakeArray(Integral, Args\&&...) fonksiyon


Belirtilen argümanları yapıcıya geçiren yeni bir [Array](../array/) nesnesi oluşturan bir fabrika işlevi.

```cpp
template<class T,class Integral,class...> std::enable_if<std::is_integral<Integral>::value, ArrayPtr<T>>::type System::MakeArray(Integral size, Args &&... args)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Fonksiyonun oluşturduğu [Array](../array/) nesnesinin öğelerinin türü |
| Integral | Dizi boyutunun tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| size | Integral | Oluşturulan dizinin boyutu. |
| args | Args\&&... | Oluşturulan [Array](../array/) nesnesinin yapıcısına geçirilen argümanlar |

### Dönüş Değeri

Oluşturulan [Array](../array/) nesnesine işaret eden bir akıllı gösterici

## İlgili Bakınız

* Typedef [ArrayPtr](../arrayptr/)
* Ad Alanı [System](../)
* Library [Aspose.Slides](../../)