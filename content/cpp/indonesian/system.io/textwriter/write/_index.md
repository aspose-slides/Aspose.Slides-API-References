---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis representasi string dari objek yang ditentukan ke aliran.
type: docs
weight: 105
url: /id/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) metode


Menulis representasi string dari objek yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objek yang akan ditulis |

## TextWriter::Write(bool) metode


Menulis representasi string dari nilai boolean yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **bool** | Nilai yang akan ditulis |

## TextWriter::Write(char_t) metode


Menulis karakter yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char_t | Nilai yang akan ditulis |

## TextWriter::Write(Decimal) metode


Menulis representasi string dari objek [Decimal](../../../system/decimal/) yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Objek yang akan ditulis |

## TextWriter::Write(double) metode


Menulis representasi string dari nilai floating point double-precision yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **double** | Nilai yang akan ditulis |

## TextWriter::Write(int) metode


Menulis representasi string dari nilai integer 32-bit yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | Nilai yang akan ditulis |

## TextWriter::Write(int64_t) metode


Menulis representasi string dari nilai integer 64-bit yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **int64_t** | Nilai yang akan ditulis |

## TextWriter::Write(float) metode


Menulis representasi string dari nilai floating point single-precision yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **float** | Nilai yang akan ditulis |

## TextWriter::Write(const String\&) metode


Menulis string yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | String yang akan ditulis |

## TextWriter::Write(uint32_t) metode


Menulis representasi string dari nilai integer tak bertanda 32-bit yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **uint32_t** | Nilai yang akan ditulis |

## TextWriter::Write(uint64_t) metode


Menulis representasi string dari nilai integer tak bertanda 64-bit yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **uint64_t** | Nilai yang akan ditulis |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) metode


Menulis semua karakter dari array yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Array yang berisi karakter yang akan ditulis |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metode


Menulis subrentang UTF-16 karakter yang ditentukan dari array karakter yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Array yang berisi karakter yang akan ditulis |
| index | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis mulai |
| count | **int32_t** | Jumlah karakter dalam subrentang yang akan ditulis; -1 menunjukkan bahwa subrentang berakhir di akhir array **buffer** |

## TextWriter::Write(const char_t *) metode


Menulis c-string yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan ditulis |

## TextWriter::Write(const TypeInfo\&) metode


Menulis representasi string dari objek [TypeInfo](../../../system/typeinfo/) yang ditentukan ke aliran.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Objek yang akan ditulis |

## TextWriter::Write(const String\&, const TArgs\&...) metode


Menulis nilai yang ditentukan dengan format yang ditentukan ke aliran.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TArgs | Daftar tipe nilai yang akan ditulis |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Format string |
| args | const TArgs\&... | Nilai yang akan ditulis |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [TextWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)