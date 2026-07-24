---
title: IndexOf()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen öğenin dizideki ilk oluşumunun indeksini belirler.
type: docs
weight: 131
url: /tr/system/array/indexof/
---
## Array::IndexOf(const T\&) const metod

Belirtilen öğenin dizideki ilk oluşumunun indeksini belirler.

```cpp
virtual int System::Array<T>::IndexOf(const T &item) const override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const T\& | Belirlenmesi gereken öğe indeksi |

### Dönüş Değeri

[Index](../../index/) belirtilen öğenin ilk oluşumu, öğe bulunursa -1, aksi takdirde

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) metod

Belirtilen öğenin dizideki ilk oluşumunun indeksini belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ArrayType | Hedef dizideki elemanların türü |
| ValueType | Dizide aranan öğenin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) belirtilen öğeyi aramak için |
| value | const [ValueType](../valuetype/)\& | Belirlenmesi gereken öğe indeksi |

### Dönüş Değeri

[Index](../../index/) belirtilen öğenin ilk oluşumu, öğe bulunursa -1, aksi takdirde

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) metod

Belirtilen indeksden başlayarak, belirtilen öğenin dizideki ilk oluşumunun indeksini belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ArrayType | Hedef dizideki elemanların türü |
| ValueType | Dizide aranan öğenin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) belirtilen öğeyi aramak için |
| value | const [ValueType](../valuetype/)\& | Belirlenmesi gereken öğe indeksi |
| startIndex | int | [Index](../../index/) aramanın başlatıldığı |

### Dönüş Değeri

[Index](../../index/) belirtilen öğenin ilk oluşumu, öğe bulunursa -1, aksi takdirde

## Array::IndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) metod

Başlangıç indeksi ve aralıktaki eleman sayısı ile belirlenen dizi öğeleri aralığında, belirtilen öğenin ilk oluşumunun indeksini belirler.

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::IndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ArrayType | Hedef dizideki elemanların türü |
| ValueType | Dizide aranan öğenin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) belirtilen öğeyi aramak için |
| value | const [ValueType](../valuetype/)\& | Belirlenmesi gereken öğe indeksi |
| startIndex | int | [Index](../../index/) aramanın başlatıldığı |
| count | int | Aranacak aralığın eleman sayısı |

### Dönüş Değeri

[Index](../../index/) belirtilen öğenin ilk oluşumu, öğe bulunursa -1, aksi takdirde

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Sınıf [Array](../)
* İsim alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)