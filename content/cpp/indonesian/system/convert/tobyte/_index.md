---
title: ToByte()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai boolean yang ditentukan ke integer tak bertanda 8-bit yang setara.
type: docs
weight: 92
url: /id/system/convert/tobyte/
---
## Convert::ToByte(bool) metode

Mengonversi nilai boolean yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) metode

Mengembalikan integer tak bertanda 8-bit yang ditentukan.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) metode

Mengonversi integer bertanda 8-bit yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) metode

Mengonversi integer tak bertanda 16-bit yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) metode

Mengonversi integer bertanda 16-bit yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) metode

Mengonversi integer tak bertanda 32-bit yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) metode

Mengonversi integer bertanda 32-bit yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) metode

Mengonversi integer tak bertanda 64-bit yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) metode

Mengonversi integer bertanda 64-bit yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) metode

Mengonversi angka float yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) metode

Mengonversi angka double yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) metode

Mengonversi angka desimal yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) metode

Mengonversi karakter unicode yang ditentukan ke integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) metode

Mengonversi string null yang ditentukan ke nilai integer tak bertanda 8-bit yang setara.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```

### Nilai Kembalian

Nol.

## Convert::ToByte(const char_t *) metode

Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi |

### Nilai Kembalian

Nilai integer tak bertanda 8-bit yang sama dengan angka yang direpresentasikan oleh c-string yang ditentukan

## Convert::ToByte(const String\&) metode

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |

### Nilai Kembalian

Nilai integer tak bertanda 8-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToByte(const String\&, int) metode

Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan ke nilai integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| from_base | int | Basis angka yang diwakili oleh string |

### Nilai Kembalian

Nilai integer tak bertanda 8-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer tak bertanda 8-bit yang setara menggunakan informasi pemformatan yang diberikan.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai integer tak bertanda 8-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) metode




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer tak bertanda 8-bit yang setara menggunakan informasi pemformatan yang diberikan serta gaya angka.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string sebuah angka |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai integer tak bertanda 8-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) metode 




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) metode 




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi nilai yang dibungkus ke nilai integer tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Shared pointer ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembalian

Nilai integer tak bertanda 8-bit yang setara dengan nilai yang dibungkus yang ditentukan

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