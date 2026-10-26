---
title: TryGetFirst()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun ilk elemanını almaya çalışır.
type: docs
weight: 248
url: /tr/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) fonksiyonu


Koleksiyonun ilk elemanını almaya çalışır.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Koleksiyon elemanlarının tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Elemanın alınacağı koleksiyon. |
| found | **bool**\& | Çıktı parametresi. Koleksiyon herhangi bir eleman içeriyorsa true döner; aksi halde false döner. |

### Dönüş Değeri

Koleksiyonun ilk elemanını döndürür. Koleksiyon boş ise tipin varsayılan değeri döndürülür.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) fonksiyonu


Koleksiyonun, verilen koşul işlevini (predicate) sağlayan ilk elemanını almaya çalışır.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Koleksiyon elemanlarının tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Elemanın alınacağı koleksiyon. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | Koşul işlevi. |
| found | **bool**\& | Çıktı parametresi. Koleksiyon herhangi bir eleman içeriyorsa true döner; aksi halde false döner. |

### Dönüş Değeri

Koleksiyonun ilk elemanını döndürür. Belirtilen koşul işlevini sağlayan bir eleman bulunamadığında tipin varsayılan değeri döndürülür.

## İlgili

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Class [Func](../../system/func/)
* Namespace [System::Collections::Generic::Details](../)
* Library [Aspose.Slides](../../)