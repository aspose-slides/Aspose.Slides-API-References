---
title: ToInt64()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai boolean yang ditentukan ke integer bertanda 64-bit yang setara.
type: docs
weight: 183
url: /id/system/convert/toint64/
---
## Convert::ToInt64(bool) metode

Mengonversi nilai boolean yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) metode

Mengonversi integer tak bertanda 8-bit yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) metode

Mengonversi integer bertanda 8-bit yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) metode

Mengonversi integer tak bertanda 16-bit yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) metode

Mengonversi integer bertanda 16-bit yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) metode

Mengonversi integer tak bertanda 32-bit yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) metode

Mengonversi integer bertanda 32-bit yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) metode

Mengonversi integer tak bertanda 64-bit yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) metode

Mengembalikan integer bertanda 64-bit yang ditentukan.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) metode

Mengonversi angka float yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) metode

Mengonversi angka double yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal\&) metode

Mengonversi angka desimal yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) metode

Mengonversi karakter unicode yang ditentukan ke integer bertanda 64-bit yang setara.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) metode

Mengonversi null-string yang ditentukan ke nilai integer 64-bit yang setara.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```

### Nilai Kembalian

Nol.

## Convert::ToInt64(const char_t *) metode

Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai integer 64-bit yang setara.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi |

### Nilai Kembalian

Nilai integer 64-bit yang sama dengan angka yang direpresentasikan oleh c-string yang ditentukan

## Convert::ToInt64(const String\&) metode

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 64-bit yang setara.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |

### Nilai Kembalian

Nilai integer 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToInt64(const String\&, int) metode

Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan ke nilai integer 64-bit yang setara.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| from_base | int | Basis angka yang direpresentasikan oleh string |

### Nilai Kembalian

Nilai integer 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 64-bit yang setara menggunakan informasi format yang disediakan.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai integer 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, std::nullptr_t) metode




```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 64-bit yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string dari angka |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai integer 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) metode




```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi nilai yang dibungkus ke nilai integer 64-bit yang setara.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Penunjuk bersama ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembalian

Nilai integer 64-bit yang setara dengan nilai yang dibungkus yang ditentukan

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)