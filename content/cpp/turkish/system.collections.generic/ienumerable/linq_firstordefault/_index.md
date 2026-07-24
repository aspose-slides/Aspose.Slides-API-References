---
title: LINQ_FirstOrDefault()
second_title: Aspose.Slides for C++ API Referansı
description: Bir dizinin ilk elemanını döndürür, ya da dizi boşsa varsayılan bir değer döndürür.
type: docs
weight: 66
url: /tr/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() metodu


Bir dizinin ilk elemanını döndürür; dizinin boş olması durumunda varsayılan bir değer döndürür.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### Dönüş Değeri

Dizideki ilk eleman veya dizi boşsa varsayılan oluşturulmuş değer.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) metodu


Bir koşulu sağlayan dizinin ilk elemanını döndürür; böyle bir eleman bulunamazsa varsayılan bir değer döndürür.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Her bir öğeyi bir koşula göre test eden bir fonksiyon. |

### Dönüş Değeri

kaynak boşsa veya öğe predicate tarafından belirtilen testi geçemiyorsa default(T); aksi takdirde, predicate tarafından belirtilen testi geçen kaynaktaki ilk öğe.

## İlgili

* Sınıf [IEnumerable](../)
* AdAlanı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)