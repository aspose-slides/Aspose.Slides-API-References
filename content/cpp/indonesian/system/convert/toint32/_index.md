---
title: ToInt32()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai boolean yang ditentukan ke integer bertanda 32-bit yang setara.
type: docs
weight: 157
url: /id/system/convert/toint32/
---
## Convert::ToInt32(bool) metode

Mengonversi nilai boolean yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) metode

Mengonversi bilangan bulat tak bertanda 8-bit yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) metode

Mengonversi bilangan bulat bertanda 8-bit yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) metode

Mengonversi bilangan bulat tak bertanda 16-bit yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) metode

Mengonversi bilangan bulat bertanda 16-bit yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) metode

Mengonversi bilangan bulat tak bertanda 32-bit yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) metode

Mengembalikan integer bertanda 32-bit yang ditentukan.

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) metode

Mengonversi bilangan bulat tak bertanda 64-bit yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) metode

Mengonversi bilangan bulat bertanda 64-bit yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) metode

Mengonversi angka float yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) metode

Mengonversi angka double yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal&) metode

Mengonversi angka desimal yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) metode

Mengonversi karakter unicode yang ditentukan ke integer bertanda 32-bit yang setara.

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) metode

Mengonversi null-string yang ditentukan ke nilai integer 32-bit yang setara.

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### Nilai Kembalian

Nol.

## Convert::ToInt32(const char_t *) metode

Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai integer 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi |

### Nilai Kembalian

Nilai integer 32-bit yang sama dengan angka yang diwakili oleh c-string yang ditentukan

## Convert::ToInt32(const String&) metode

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |

### Nilai Kembalian

Nilai integer 32-bit yang sama dengan angka yang diwakili oleh string yang ditentukan

## Convert::ToInt32(const String&, int) metode

Mengonversi string yang berisi representasi string dari sebuah angka dalam basis yang ditentukan ke nilai integer 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| from_base | int | Basis angka yang diwakili oleh string |

### Nilai Kembalian

Nilai integer 32-bit yang sama dengan angka yang diwakili oleh string yang ditentukan

## Convert::ToInt32(const String&, const SharedPtr<IFormatProvider>&) metode

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 32-bit yang setara menggunakan informasi pemformatan yang diberikan.

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai integer 32-bit yang sama dengan angka yang diwakili oleh string yang ditentukan

## Convert::ToInt32(const String&, const SharedPtr<Globalization::CultureInfo>&) metode




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String&, const SharedPtr<Globalization::NumberFormatInfo>&) metode




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String&, std::nullptr_t) metode




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&) metode

Mengonversi string yang berisi representasi string dari sebuah angka ke nilai integer 32-bit yang setara menggunakan informasi pemformatan dan gaya angka yang diberikan.

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | string yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise nilai enum NumberStyles yang menentukan gaya representasi string yang diizinkan |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai integer 32-bit yang sama dengan angka yang diwakili oleh string yang ditentukan

## Convert::ToInt32(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&) metode




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&) metode




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) metode




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr<Object>&, const SharedPtr<IFormatProvider>&) metode

Mengonversi nilai yang dibungkus ke nilai integer 32-bit yang setara.

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | shared pointer ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembalian

Nilai integer 32-bit yang setara dengan nilai yang dibungkus

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