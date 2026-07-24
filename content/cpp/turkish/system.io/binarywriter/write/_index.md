---
title: Write()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen işaretsiz 8-bit tamsayı değerini çıktı akışına yazar.
type: docs
weight: 92
url: /tr/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) metodu


Belirtilen işaretsiz 8-bit tamsayı değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **uint8_t** | Yazılacak değer |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) metodu


Belirtilen bayt dizisinden belirtilen bayt alt aralığını çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Yazılacak baytları içeren dizi |
| index | int | **buffer** içinde yazma alt aralığının başladığı 0 tabanlı indeks |
| count | int | Yazılacak alt aralığın eleman sayısı; -1, alt aralığın **buffer** dizisinin sonuna kadar devam ettiğini belirtir |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) metodu


Belirtilen karakter dizisinden belirtilen UTF-16 karakter alt aralığını çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Yazılacak karakterleri içeren dizi |
| index | int | **buffer** içinde yazma alt aralığının başladığı 0 tabanlı indeks |
| count | int | Yazılacak alt aralığın karakter sayısı; -1, alt aralığın **buffer** dizisinin sonuna kadar devam ettiğini belirtir |

## BinaryWriter::Write(bool) metodu


**value** true ise 0, false ise 1 değerinde tek bayt çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **bool** | Çıktı akışına yazılacak baytın değerini belirten boolean değer |

## BinaryWriter::Write(char16_t) metodu


Belirtilen 16-bit genişliğindeki karakter değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char16_t | Yazılacak değer |

## BinaryWriter::Write(int16_t) metodu


Belirtilen 16-bit tamsayı değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **int16_t** | Yazılacak değer |

## BinaryWriter::Write(int) metodu


Belirtilen 32-bit tamsayı değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int | Yazılacak değer |

## BinaryWriter::Write(int64_t) metodu


Belirtilen 64-bit tamsayı değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **int64_t** | Yazılacak değer |

## BinaryWriter::Write(uint16_t) metodu


Belirtilen işaretsiz 16-bit tamsayı değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **uint16_t** | Yazılacak değer |

## BinaryWriter::Write(uint32_t) metodu


Belirtilen işaretsiz 32-bit tamsayı değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **uint32_t** | Yazılacak değer |

## BinaryWriter::Write(uint64_t) metodu


Belirtilen işaretsiz 64-bit tamsayı değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **uint64_t** | Yazılacak değer |

## BinaryWriter::Write(float) metodu


Belirtilen tek duyarlıklı kayan nokta değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **float** | Yazılacak değer |

## BinaryWriter::Write(double) metodu


Belirtilen çift duyarlıklı kayan nokta değerini çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | **double** | Yazılacak değer |

## BinaryWriter::Write(const Decimal\&) metodu


Belirtilen [Decimal](../../../system/decimal/) değerinin bayt temsili çıkt akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | Yazılacak değer |

## BinaryWriter::Write(const String\&) metodu


Geçerli kodlamada uzunluk ön ekli bir dizeyi çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Yazılacak dize |

## BinaryWriter::Write(const char_t *) metodu


Geçerli kodlamada uzunluk ön ekli bir dizeyi çıktı akışına yazar.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const char_t * | Yazılacak C-dizesi |

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [BinaryWriter](../)
* Sınıf [Decimal](../../../system/decimal/)
* Sınıf [String](../../../system/string/)
* İsim Uzayı [System::IO](../../)
* Kütüphane [Aspose.Slides](../../../)