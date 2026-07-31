---
title: ToUInt32()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai boolean yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.
type: docs
weight: 170
url: /id/system/convert/touint32/
---
## Convert::ToUInt32(bool) metode


Mengonversi nilai boolean yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) metode


Mengonversi integer tak bertanda 8-bit yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) metode


Mengonversi integer bertanda 8-bit yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) metode


Mengonversi integer tak bertanda 16-bit yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) metode


Mengonversi integer bertanda 16-bit yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) metode


Mengembalikan integer tak bertanda 32-bit yang ditentukan.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) metode


Mengonversi integer bertanda 32-bit yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) metode


Mengonversi integer tak bertanda 64-bit yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) metode


Mengonversi integer bertanda 64-bit yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) metode


Mengonversi angka float yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) metode


Mengonversi angka double yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) metode


Mengonversi angka desimal yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) metode


Mengonversi karakter unicode yang ditentukan menjadi integer tak bertanda 32-bit yang ekuivalen.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) metode


Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) metode


Mengonversi null-string yang ditentukan menjadi nilai integer tak bertanda 32-bit yang ekuivalen.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```


### Nilai Kembali

Nol.

## Convert::ToUInt32(const char_t *) metode


Mengonversi c-string yang berisi representasi string dari sebuah angka menjadi nilai integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | C-string yang akan dikonversi |

### Nilai Kembali

Nilai integer tak bertanda 32-bit yang sama dengan angka yang direpresentasikan oleh c-string yang ditentukan

## Convert::ToUInt32(const String\&) metode


Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |

### Nilai Kembali

Nilai integer tak bertanda 32-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToUInt32(const String\&, int) metode


Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan menjadi nilai integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| from_base | int | Basis dari angka yang direpresentasikan oleh string |

### Nilai Kembali

Nilai integer tak bertanda 32-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai integer tak bertanda 32-bit yang ekuivalen menggunakan informasi format yang disediakan.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembali

Nilai integer tak bertanda 32-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) metode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi string yang berisi representasi string dari sebuah angka menjadi nilai integer tak bertanda 32-bit yang ekuivalen menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string dari sebuah angka |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembali

Nilai integer tak bertanda 32-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) metode




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi nilai yang dibungkus menjadi nilai integer tak bertanda 32-bit yang ekuivalen.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Penunjuk bersama ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembali

Nilai integer tak bertanda 32-bit yang ekuivalen dengan nilai yang dibungkus yang ditentukan

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