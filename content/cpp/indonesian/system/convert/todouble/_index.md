---
title: ToDouble()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai boolean yang ditentukan menjadi angka floating-point double presisi yang setara.
type: docs
weight: 222
url: /id/system/convert/todouble/
---
## Convert::ToDouble(bool) metode

Mengonversi nilai boolean yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) metode

Mengonversi unsigned integer 8-bit yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) metode

Mengonversi signed integer 8-bit yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) metode

Mengonversi unsigned integer 16-bit yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) metode

Mengonversi signed integer 16-bit yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) metode

Mengonversi unsigned integer 32-bit yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) metode

Mengonversi signed integer 32-bit yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) metode

Mengonversi unsigned integer 64-bit yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) metode

Mengonversi signed integer 64-bit yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) metode

Mengonversi angka single-precision yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) metode

Mengembalikan angka double yang ditentukan.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) metode

Mengonversi angka desimal yang ditentukan menjadi angka floating-point double presisi yang setara.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) metode

Mengonversi null-string yang ditentukan menjadi nilai floating-point double presisi yang setara.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```

### Nilai Kembali

Nol.

## Convert::ToDouble(const char_t *) metode

Mengonversi c-string yang berisi representasi string dari sebuah angka menjadi nilai floating-point double presisi yang setara.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi |

### Nilai Kembali

Nilai floating-point double presisi yang sama dengan angka yang direpresentasikan oleh c-string yang ditentukan

## Convert::ToDouble(const String\&) metode

Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai floating-point double presisi yang setara.

```cpp
static double System::Convert::ToDouble(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |

### Nilai Kembali

Nilai floating-point double presisi yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai floating-point double presisi yang setara menggunakan informasi format yang diberikan.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembali

Nilai floating-point double presisi yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) metode




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai floating-point double presisi yang setara menggunakan informasi format dan gaya angka yang diberikan.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string dari sebuah angka |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembali

Nilai floating-point double presisi yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi nilai yang dibungkus menjadi nilai floating-point double presisi. Jika tipe nilai yang dibungkus adalah [String](../../string/), format string yang ditentukan akan digunakan selama konversi.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Penunjuk bersama ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembali

Nilai floating-point double presisi yang setara dengan nilai yang dibungkus yang ditentukan

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Decimal](../../decimal/)
* Kelas [DateTime](../../datetime/)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Kelas [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)