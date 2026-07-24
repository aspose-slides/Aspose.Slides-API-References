---
title: BitConverter
second_title: Aspose.Slides için C++ API Referansı
description: Bayt dizisinin bir değer tipine ve tersine dönüşüm yapan yöntemler içerir. Bu, örnek hizmetleri olmayan static bir türdür. Herhangi bir yolla onun örneklerini asla oluşturmayın.
type: docs
weight: 66
url: /tr/system/bitconverter/
---
## BitConverter sınıfı


Bayt dizisinin bir değer tipine ve tersine dönüşüm yapan yöntemler içerir. Bu, static bir türdür ve örnek hizmetleri yoktur. Herhangi bir yolla onun örneklerini asla oluşturmayın.

```cpp
class BitConverter
```

## Yöntemler

| Method | Description |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | Mevcut mimarinin uçuçluk durumunu gösterir. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | Belirtilen çift duyarlıklı kayan nokta değerinin ikili gösterimiyle aynı ikili gösterime sahip bir 64-bit tam sayı değeri döndürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | Belirtilen boolean değeri bir bayt dizisine dönüştürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | Belirtilen char_t değerini bir bayt dizisine dönüştürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | Belirtilen 16-bit tam sayı değerini bir bayt dizisine dönüştürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | Belirtilen 32-bit tam sayı değerini bir bayt dizisine dönüştürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | Belirtilen 64-bit tam sayı değerini bir bayt dizisine dönüştürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | Belirtilen işaretsiz 16-bit tam sayı değerini bir bayt dizisine dönüştürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | Belirtilen işaretsiz 32-bit tam sayı değerini bir bayt dizisine dönüştürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | Belirtilen işaretsiz 64-bit tam sayı değerini bir bayt dizisine dönüştürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | Belirtilen tek duyarlıklı kayan nokta değerini bir bayt dizisine dönüştürür. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | Belirtilen çift duyarlıklı kayan nokta değerini bir bayt dizisine dönüştürür. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | Parametre değeriyle eşdeğer bir çift duyarlıklı kayan nokta değeri döndürür. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan bir baytı boolean değerine dönüştürür. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan bir baytı boolean değerine dönüştürür. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan iki baytı char_t değerine dönüştürür. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan iki baytı char_t değerine dönüştürür. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan sekiz baytı çift duyarlıklı kayan nokta değerine dönüştürür. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan sekiz baytı çift duyarlıklı kayan nokta değerine dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan iki baytı 16-bit tam sayı değerine dönüştürür. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan iki baytı 16-bit tam sayı değerine dönüştürür. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan dört baytı 32-bit tam sayı değerine dönüştürür. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan dört baytı 32-bit tam sayı değerine dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan sekiz baytı 64-bit tam sayı değerine dönüştürür. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan sekiz baytı 64-bit tam sayı değerine dönüştürür. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan dört baytı tek duyarlıklı kayan nokta değerine dönüştürür. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan dört baytı tek duyarlıklı kayan nokta değerine dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | Belirtilen bayt dizisinin tüm değerlerini onaltılık string temsiline dönüştürür. Onaltılık gösterimde kullanılacak harflerin büyük/küçük olması ve komşu bayt çiftleri arasına eklenecek ayraç, ilgili argümanlarla belirtilir. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen bayt dizisinin değerlerini belirtilen indeksten itibaren onaltılık string temsiline dönüştürür. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | Belirtilen bayt dizisinin bir değer aralığını onaltılık string temsiline dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan iki baytı işaretsiz 16-bit tam sayı değerine dönüştürür. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan iki baytı işaretsiz 16-bit tam sayı değerine dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan dört baytı işaretsiz 32-bit tam sayı değerine dönüştürür. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan dört baytı işaretsiz 32-bit tam sayı değerine dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan sekiz baytı işaretsiz 64-bit tam sayı değerine dönüştürür. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | Belirtilen dizinin belirtilen indeksiyle başlayan sekiz baytı işaretsiz 64-bit tam sayı değerine dönüştürür. |
## Alanlar

| Field | Description |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | Mevcut mimarinin uçuçluk durumunu gösterir. Mimari küçük uçlu (little endian) ise true, aksi takdirde false döner. |
## Açıklamalar



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // Yazdırılacak değerleri oluştur.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // Değeri ve baytlarını yazdır.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## Ayrıca

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)