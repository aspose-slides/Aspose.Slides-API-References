---
title: ToSingle()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengkonversi nilai boolean yang ditentukan ke angka floating-point presisi tunggal yang setara.
type: docs
weight: 209
url: /id/system/convert/tosingle/
---
## Convert::ToSingle(bool) metode

Mengkonversi nilai boolean yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) metode

Mengkonversi bilangan bulat tak bertanda 8-bit yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) metode

Mengkonversi bilangan bulat bertanda 8-bit yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) metode

Mengkonversi bilangan bulat tak bertanda 16-bit yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) metode

Mengkonversi bilangan bulat bertanda 16-bit yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) metode

Mengkonversi bilangan bulat tak bertanda 32-bit yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) metode

Mengkonversi bilangan bulat bertanda 32-bit yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) metode

Mengkonversi bilangan bulat tak bertanda 64-bit yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) metode

Mengkonversi bilangan bulat bertanda 64-bit yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) metode

Mengembalikan angka float yang ditentukan.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) metode

Mengkonversi angka double presisi ganda yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) metode

Mengkonversi angka desimal yang ditentukan ke angka floating-point presisi tunggal yang setara.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) metode

Mengkonversi null-string yang ditentukan ke nilai floating-point presisi tunggal yang setara.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### Nilai Kembalian

Zero.

## Convert::ToSingle(const char_t *) metode

Mengkonversi c-string yang berisi representasi string dari sebuah angka ke nilai floating-point presisi tunggal yang setara.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang sama dengan angka yang direpresentasikan oleh c-string yang ditentukan

## Convert::ToSingle(const String\&) metode

Mengkonversi string yang berisi representasi string dari sebuah angka ke nilai floating-point presisi tunggal yang setara.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengkonversi string yang berisi representasi string dari sebuah angka ke nilai floating-point presisi tunggal yang setara menggunakan informasi format yang diberikan.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) metode




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengkonversi string yang berisi representasi string dari sebuah angka ke nilai floating-point presisi tunggal yang setara menggunakan informasi format dan gaya angka yang diberikan.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya representasi string yang diizinkan |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengkonversi nilai yang dibungkus (boxed) yang ditentukan ke nilai floating-point presisi tunggal.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Penunjuk bersama ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang setara dengan nilai yang dibungkus yang ditentukan

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
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)