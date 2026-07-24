---
title: ByteLength()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen dizinin tüm elemanları tarafından kullanılan bayt sayısını belirler.
type: docs
weight: 14
url: /tr/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) method


Belirtilen dizinin tüm elemanları tarafından kullanılan bayt sayısını belirler.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Dizinin elemanlarının türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Bir dizi |

### Dönüş Değeri

Belirtilen dizinin tüm elemanları tarafından kullanılan bayt sayısı

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) method


Belirtilen dizi görünümünün tüm elemanları tarafından kullanılan bayt sayısını belirler.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Dizi görünümünün elemanlarının türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Bir dizi görünümü |

### Dönüş Değeri

Belirtilen dizi görünümünün tüm elemanları tarafından kullanılan bayt sayısı

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) method


Belirtilen yığın dizisinin tüm elemanları tarafından kullanılan bayt sayısını belirler.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Yığın dizisinin elemanlarının türü |
| N | Yığın dizisinin boyutu |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Bir yığın dizisi |

### Dönüş Değeri

Belirtilen yığın dizisinin tüm elemanları tarafından kullanılan bayt sayısı

## İlgili

* Typedef [SharedPtr](../../sharedptr/)
* Sınıf [Array](../../array/)
* Sınıf [Buffer](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)