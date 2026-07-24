---
title: SetByte()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt değerini belirtilen bayt offsetinde ayarlar.
type: docs
weight: 40
url: /tr/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) yöntemi


Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt değerini belirtilen bayt offsetinde ayarlar.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Dizinin elemanlarının tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Hedef dizi |
| index | int | Ayarlanacak baytın sıfır tabanlı offseti |
| value | **uint8_t** | Ayarlanacak bayt değeri |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) yöntemi


Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt değerini belirtilen bayt offsetinde ayarlar.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Dizinin elemanlarının tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Hedef dizi görünümü |
| index | int | Ayarlanacak baytın sıfır tabanlı offseti |
| value | **uint8_t** | Ayarlanacak bayt değeri |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) yöntemi


Belirtilen tipli diziyi ham bayt dizisi olarak yorumlar ve belirtilen bayt değerini belirtilen bayt offsetinde ayarlar.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Dizinin elemanlarının tipi |
| N | Yığın dizisinin boyutu |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Hedef yığın dizisi |
| index | int | Ayarlanacak baytın sıfır tabanlı offseti |
| value | **uint8_t** | Ayarlanacak bayt değeri |

## Diğer Bilgiler

* Tip Tanımı [SharedPtr](../../sharedptr/)
* Sınıf [Array](../../array/)
* Sınıf [Buffer](../)
* İsim Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)