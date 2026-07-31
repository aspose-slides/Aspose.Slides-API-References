---
title: ToBoolean()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai boolean yang ditentukan.
type: docs
weight: 79
url: /id/system/convert/toboolean/
---
## Convert::ToBoolean(bool) metode

Mengembalikan nilai boolean yang ditentukan.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```
## Convert::ToBoolean(uint8_t) metode

Mengonversi integer tak bertanda 8-bit yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```
## Convert::ToBoolean(int8_t) metode

Mengonversi integer bertanda 8-bit yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```
## Convert::ToBoolean(uint16_t) metode

Mengonversi integer tak bertanda 16-bit yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```
## Convert::ToBoolean(int16_t) metode

Mengonversi integer bertanda 16-bit yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```
## Convert::ToBoolean(uint32_t) metode

Mengonversi integer tak bertanda 32-bit yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```
## Convert::ToBoolean(int32_t) metode

Mengonversi integer bertanda 32-bit yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```
## Convert::ToBoolean(uint64_t) metode

Mengonversi integer tak bertanda 64-bit yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```
## Convert::ToBoolean(int64_t) metode

Mengonversi integer bertanda 64-bit yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```
## Convert::ToBoolean(float) metode

Mengonversi angka float yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```
## Convert::ToBoolean(double) metode

Mengonversi angka double yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```
## Convert::ToBoolean(const Decimal\&) metode

Mengonversi angka desimal yang ditentukan menjadi nilai boolean yang setara.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```
## Convert::ToBoolean(char_t) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```
## Convert::ToBoolean(DateTime) metode

Konversi tidak didukung. Selalu melempar InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```
## Convert::ToBoolean(std::nullptr_t) metode

Mengonversi null-string yang ditentukan menjadi nilai boolean yang setara.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Nilai Kembali

False.

## Convert::ToBoolean(const char_t *) metode

Mengonversi c-string yang ditentukan menjadi nilai tipe bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dikonversi |

### Nilai Kembali

True jika c-string yang ditentukan sama dengan "True" dan false jika c-string yang ditentukan sama dengan "False".

## Convert::ToBoolean(const String\&) metode

Mengonversi string yang ditentukan menjadi nilai tipe bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |

### Nilai Kembali

True jika string yang ditentukan sama dengan "True" dan false jika string yang ditentukan sama dengan "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan menjadi nilai tipe bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi |

### Nilai Kembali

True jika string yang ditentukan sama dengan "True" dan false jika string yang ditentukan sama dengan "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi nilai yang dibungkus menjadi nilai boolean yang setara.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Pointer bersama ke objek yang membungkus nilai untuk dikonversi |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Format string yang akan digunakan jika tipe nilai yang dibungkus adalah [String](../../string/) |

### Nilai Kembali

Nilai boolean yang setara dengan nilai yang dibungkus.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Decimal](../../decimal/)
* Kelas [DateTime](../../datetime/)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [Object](../../object/)
* Struktur [Convert](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)