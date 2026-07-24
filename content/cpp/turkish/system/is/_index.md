---
title: Is()
second_title: Aspose.Slides için C++ API Referansı
description: "'is' bildirim deseni çevirisini uygular."
type: docs
weight: 2302
url: /tr/system/is/
---
## System::Is(const ExpressionT\&, ResultT\&) fonksiyon


‘is’ bildirimi deseni çevirisini uygular.

```cpp
template<class PatternT,class ExpressionT,class ResultT> bool System::Is(const ExpressionT &left, ResultT &result)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| PatternT | kontrol edilecek tip. |
| ExpressionT | sol ifadeye ait tip. |
| ResultT | sonuç ifadesinin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | const ExpressionT\& | kontrol edilecek ifade. |
| result | ResultT\& | kontrol edilen tipe atanacak değişken. |

### Dönüş Değeri

type check başarılıysa true, aksi takdirde false.

## System::Is(const ExpressionT\&, const ConstantT\&) fonksiyon


‘is’ sabit deseni çevirisini uygular.

```cpp
template<class ExpressionT,class ConstantT> std::enable_if_t<!std::is_base_of<Details::Pattern, ConstantT>::value, bool> System::Is(const ExpressionT &left, const ConstantT &constant)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ExpressionT | sol ifadeye ait tip. |
| ConstantT | sabit ifadenin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | const ExpressionT\& | kontrol edilecek ifade. |
| constant | const ConstantT\& | sol ifade ile karşılaştırılacak sabit ifade. |

### Dönüş Değeri

type check başarılıysa true, aksi takdirde false.

## System::Is(const E\&, const A\&) fonksiyon


Üst seviye eşleme fonksiyonu. Bir modele bir değere uygulanır.

```cpp
template<typename A,typename E> std::enable_if_t<std::is_base_of<Details::Pattern, A>::value, bool> System::Is(const E &e, const A &a)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| A | Model tipi (Details::Pattern'den türemelidir). |
| E | eşleşecek değerin tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| e | const E\& | eşleşecek değer. |
| a | const A\& | uygulanacak model. |

### Dönüş Değeri

model değere uygunsa true.

## İlgili

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)