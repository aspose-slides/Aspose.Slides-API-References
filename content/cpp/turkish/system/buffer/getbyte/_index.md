---
title: GetByte()
second_title: Aspose.Slides C++ için API Referansı
description: Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt offsetindeki bayt değerini alır.
type: docs
weight: 27
url: /tr/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) metod


Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt offsetindeki bayt değerini alır.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Dizinin öğelerinin türü |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Hedef dizi |
| index | int | Alınacak baytın sıfır tabanlı offseti |

### Dönüş Değeri

Belirtilen dizindeki bayt değeri

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) metod


Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt offsetindeki bayt değerini alır.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Dizi görünümünün öğelerinin türü |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Hedef dizi görünümü |
| index | int | Alınacak baytın sıfır tabanlı offseti |

### Dönüş Değeri

Belirtilen dizindeki bayt değeri

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) metod


Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt offsetindeki bayt değerini alır.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```


### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| T | Yığın dizisinin öğelerinin türü |
| N | Yığın dizisinin boyutu |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Hedef yığın dizisi |
| index | int | Alınacak baytın sıfır tabanlı offseti |

### Dönüş Değeri

Belirtilen dizindeki bayt değeri

## Bakınız

* Tip Tanımı [SharedPtr](../../sharedptr/)
* Sınıf [Array](../../array/)
* Sınıf [Buffer](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)