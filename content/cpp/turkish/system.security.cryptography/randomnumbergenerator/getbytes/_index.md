---
title: GetBytes()
second_title: C++ için Aspose.Slides API Referansı
description: Mevcut dizi öğelerini rastgele baytlarla doldurur.
type: docs
weight: 14
url: /tr/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) metod


Mevcut dizi öğelerini rastgele baytlarla doldurur.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Doldurulacak bayt dizisi. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) metod


Mevcut dizi dilimini rastgele baytlarla doldurur.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dilim doldurulacak bayt dizisi. |
| offset | int | Dilim başlangıç indeksi. |
| count | int | Dilim boyutu. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) metod


Mevcut dizi görünümü öğelerini rastgele baytlarla doldurur.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Doldurulacak bayt dizi görünümü. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) metod


Mevcut dizi görünümü dilimini rastgele baytlarla doldurur.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Dilim doldurulacak bayt dizi görünümü. |
| offset | int | Dilim başlangıç indeksi. |
| count | int | Dilim boyutu. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) metod


Mevcut yığın dizisi öğelerini rastgele baytlarla doldurur.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Doldurulacak bayt yığın dizisi. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) metod


Mevcut yığın dizi dilimini rastgele baytlarla doldurur.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Dilim doldurulacak bayt yığın dizisi. |
| offset | int | Dilim başlangıç indeksi. |
| count | int | Dilim boyutu. |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [RandomNumberGenerator](../)
* İsim Alanı [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)