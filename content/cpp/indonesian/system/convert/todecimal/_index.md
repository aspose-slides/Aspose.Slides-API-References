---
title: ToDecimal()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi nilai boolean yang ditentukan ke angka desimal yang setara.
type: docs
weight: 235
url: /id/system/convert/todecimal/
---
## Convert::ToDecimal(bool) metode


Mengonversi nilai boolean yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) metode


Mengonversi bilangan bulat tak bertanda 8-bit yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) metode


Mengonversi bilangan bulat bertanda 8-bit yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) metode


Mengonversi bilangan bulat tak bertanda 16-bit yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) metode


Mengonversi bilangan bulat bertanda 16-bit yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) metode


Mengonversi bilangan bulat tak bertanda 32-bit yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) metode


Mengonversi bilangan bulat bertanda 32-bit yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) metode


Mengonversi bilangan bulat tak bertanda 64-bit yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) metode


Mengonversi bilangan bulat bertanda 64-bit yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) metode


Mengonversi angka float yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) metode


Mengonversi angka double yang ditentukan ke angka desimal yang setara.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) metode


Mengembalikan angka desimal yang ditentukan.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) metode


Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) metode


Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) metode


Mengonversi null-string yang ditentukan ke nilai [Decimal](../../decimal/) yang setara.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```


### Nilai Kembalian

Nol.

## Convert::ToDecimal(const char_t *) metode


Mengonversi c-string yang berisi representasi string dari sebuah angka ke nilai [Decimal](../../decimal/) yang setara.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi |

### Nilai Kembalian

Nilai [Decimal](../../decimal/) yang sama dengan angka yang diwakili oleh c-string yang ditentukan

## Convert::ToDecimal(const String\&) metode


Mengonversi string yang berisi representasi string dari sebuah angka ke nilai [Decimal](../../decimal/) yang setara.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |

### Nilai Kembalian

Nilai [Decimal](../../decimal/) yang sama dengan angka yang diwakili oleh string yang ditentukan

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi string yang berisi representasi string dari sebuah angka ke nilai [Decimal](../../decimal/) yang setara menggunakan informasi format yang diberikan.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai [Decimal](../../decimal/) yang sama dengan angka yang diwakili oleh string yang ditentukan

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi string yang berisi representasi string dari sebuah angka ke nilai [Decimal](../../decimal/) yang setara menggunakan gaya angka dan informasi format yang ditentukan.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise nilai enum NumberStyles yang menentukan gaya representasi string angka yang diizinkan |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string |

### Nilai Kembalian

Nilai [Decimal](../../decimal/) yang sama dengan angka yang diwakili oleh string yang ditentukan

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi nilai yang dibungkus menjadi nilai [Decimal](../../decimal/) yang setara.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | SharedPtr ke objek yang membungkus nilai yang akan dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembalian

Nilai [Decimal](../../decimal/) yang setara dengan nilai yang dibungkus yang ditentukan

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Decimal](../../decimal/)
* Kelas [DateTime](../../datetime/)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)