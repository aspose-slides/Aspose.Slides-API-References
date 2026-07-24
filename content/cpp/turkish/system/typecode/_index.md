---
title: TypeCode
second_title: Aspose.Slides for C++ API Referansı
description: Bir nesnenin tipini temsil eder.
type: docs
weight: 3225
url: /tr/system/typecode/
---
## TypeCode enum

Bir nesnenin türünü temsil eder.

```cpp
enum class TypeCode
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Empty | 0 | Null bir referans. |
| Object | 1 | Başka bir TypeCode tarafından açıkça temsil edilmeyen herhangi bir referans ya da değer tipini temsil eden genel bir tip. |
| DBNull | 2 | Bir veritabanı null (sütun) değeri. |
| Boolean | 3 | [Boolean](../boolean/) değerleri true veya false olan basit bir tip. |
| Char | 4 | 0 ile 65535 arasında değerleri olan işaretsiz 16-bit tam sayıları temsil eden bütünsel bir tip. |
| SByte | 5 | -128 ile 127 arasında değerleri olan işaretli 8-bit tam sayıları temsil eden bütünsel bir tip. |
| Byte | 6 | 0 ile 255 arasında değerleri olan işaretsiz 8-bit tam sayıları temsil eden bütünsel bir tip. |
| Int16 | 7 | -32768 ile 32767 arasında değerleri olan işaretli 16-bit tam sayıları temsil eden bütünsel bir tip. |
| UInt16 | 8 | 0 ile 65535 arasında değerleri olan işaretsiz 16-bit tam sayıları temsil eden bütünsel bir tip. |
| Int32 | 9 | -2147483648 ile 2147483647 arasında değerleri olan işaretli 32-bit tam sayıları temsil eden bütünsel bir tip. |
| UInt32 | 10 | 0 ile 4294967295 arasında değerleri olan işaretsiz 32-bit tam sayıları temsil eden bütünsel bir tip. |
| Int64 | 11 | -9223372036854775808 ile 9223372036854775807 arasında değerleri olan işaretli 64-bit tam sayıları temsil eden bütünsel bir tip. |
| UInt64 | 12 | 0 ile 18446744073709551615 arasında değerleri olan işaretsiz 64-bit tam sayıları temsil eden bütünsel bir tip. |
| Single | 13 | Yaklaşık 1.5 x 10 -45 ile 3.4 x 10 38 arasında değişen ve 7 basamak kesinliğe sahip değerleri temsil eden kayan nokta tipi. |
| Double | 14 | Yaklaşık 5.0 x 10 -324 ile 1.7 x 10 308 arasında değişen ve 15-16 basamak kesinliğe sahip değerleri temsil eden kayan nokta tipi. |
| Decimal | 15 | 1.0 x 10 -28 ile yaklaşık 7.9 x 10 28 arasında değişen ve 28-29 anlamlı basamağa sahip değerleri temsil eden basit bir tip. |
| DateTime | 16 | Bir tarih ve saat değerini temsil eden bir tip. |
| String | 18 | Unicode karakter dizilerini temsil eden mühürlenmiş sınıf tipi. |

## İlgili

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)