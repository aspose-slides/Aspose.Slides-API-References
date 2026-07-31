---
title: ToSByte()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai boolean yang ditentukan ke integer bertanda 8-bit yang setara.
type: docs
weight: 105
url: /id/system/convert/tosbyte/
---
## Convert::ToSByte(bool) method

Mengonversi nilai boolean yang ditentukan ke integer bertanda 8-bit yang setara.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) method

Mengonversi 8-bit unsigned integer yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) method

Mengembalikan 8-bit signed integer yang ditentukan.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) method

Mengonversi 16-bit unsigned integer yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) method

Mengonversi 16-bit signed integer yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) method

Mengonversi 32-bit unsigned integer yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) method

Mengonversi 32-bit signed integer yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) method

Mengonversi 64-bit unsigned integer yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) method

Mengonversi 64-bit signed integer yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) method

Mengonversi angka float yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) method

Mengonversi angka double yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) method

Mengonversi angka decimal yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) method

Mengonversi karakter unicode yang ditentukan ke 8-bit signed integer yang setara.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) method

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) method

Mengonversi null-string yang ditentukan ke nilai integer 8-bit yang setara.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### Nilai Kembalian

Nol.

## Convert::ToSByte(const char_t *) method

Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai integer 8-bit yang setara.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi |

### Nilai Kembalian

Nilai integer 8-bit yang sama dengan angka yang direpresentasikan oleh c-string yang ditentukan

## Convert::ToSByte(const String\&) method

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 8-bit yang setara.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |

### Nilai Kembalian

Nilai integer 8-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToSByte(const String\&, int) method

Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan ke nilai integer 8-bit yang setara.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| from_base | int | basis angka yang direpresentasikan oleh string |

### Nilai Kembalian

Nilai integer 8-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai unsigned 8-bit integer yang setara menggunakan informasi pemformatan yang diberikan.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai unsigned 8-bit integer yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) method 




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai 8-bit integer yang setara menggunakan informasi pemformatan yang diberikan dan gaya angka.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string angka |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai unsigned 8-bit integer yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method 




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) method 




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) method 




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

Mengonversi nilai yang dibungkus ke nilai integer 8-bit yang setara.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Penunjuk bersama ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembalian

Nilai integer 8-bit yang setara dengan nilai yang dibungkus yang ditentukan

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)