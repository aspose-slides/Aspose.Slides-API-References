---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengoutput representasi string dari objek yang ditentukan ke aliran output standar.
type: docs
weight: 1
url: /id/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) method

Mengoutput representasi string dari objek yang ditentukan ke aliran output standar.

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek yang akan dioutput |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) untuk dioutput |

## Console::Write(bool) method

Mengoutput representasi string dari nilai bool ke aliran output standar.

```cpp
static void System::Console::Write(bool value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **bool** | Nilai yang akan dioutput |

## Console::Write(char_t) method

Mengoutput nilai karakter yang ditentukan ke aliran output standar.

```cpp
static void System::Console::Write(char_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char_t | Nilai yang akan dioutput |

## Console::Write(const ArrayPtr\<char_t\>\&) method

Mengoutput representasi string dari array karakter yang ditentukan ke aliran output standar.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Array yang akan dioutput |

## Console::Write(const Decimal\&) method

Mengoutput representasi string dari nilai [Decimal](../../decimal/) ke aliran output standar.

```cpp
static void System::Console::Write(const Decimal &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Nilai yang akan dioutput |

## Console::Write(double) method

Mengoutput representasi string dari nilai titik mengambang double-precision ke aliran output standar.

```cpp
static void System::Console::Write(double value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **double** | Nilai yang akan dioutput |

## Console::Write(float) method

Mengoutput representasi string dari nilai titik mengambang single-precision ke aliran output standar.

```cpp
static void System::Console::Write(float value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **float** | Nilai yang akan dioutput |

## Console::Write(int32_t) method

Mengoutput representasi string dari nilai integer 32-bit ke aliran output standar.

```cpp
static void System::Console::Write(int32_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **int32_t** | Nilai yang akan dioutput |

## Console::Write(int64_t) method

Mengoutput representasi string dari nilai integer 64-bit ke aliran output standar.

```cpp
static void System::Console::Write(int64_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **int64_t** | Nilai yang akan dioutput |

## Console::Write(const String\&) method

Mengoutput objek string yang ditentukan ke aliran output standar.

```cpp
static void System::Console::Write(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | Objek string yang akan dioutput |

## Console::Write(const char_t *) method

Mengoutput c-string yang ditentukan ke aliran output standar.

```cpp
static void System::Console::Write(const char_t *value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | c-string yang akan dioutput |

## Console::Write(const TypeInfo\&) method

Mengoutput representasi string dari nilai [TypeInfo](../../typeinfo/) ke aliran output standar.

```cpp
static void System::Console::Write(const TypeInfo &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Nilai yang akan dioutput |

## Console::Write(uint32_t) method

Mengoutput representasi string dari nilai integer tak bertanda 32-bit ke aliran output standar.

```cpp
static void System::Console::Write(uint32_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **uint32_t** | Nilai yang akan dioutput |

## Console::Write(uint64_t) method

Mengoutput representasi string dari nilai integer tak bertanda 64-bit ke aliran output standar.

```cpp
static void System::Console::Write(uint64_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **uint64_t** | Nilai yang akan dioutput |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method

Mengoutput representasi string dari rentang yang ditentukan dari array karakter yang ditentukan ke aliran output standar.

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Array karakter |
| index | **int32_t** | Indeks dalam array tempat rentang yang akan dioutput dimulai |
| count | **int32_t** | Jumlah elemen dalam rentang yang akan dioutput |

## Console::Write(const String\&, Args\&&...) method

Mengoutput representasi string dari argumen yang ditentukan yang diformat menurut format yang ditentukan ke aliran output standar.

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| The | tipe nilai yang akan dioutput |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../../string/)\& | Format string |
| args | Args\&&... | Nilai yang akan dioutput |

## Console::Write(const char *) method




```cpp
static void System::Console::Write(const char *)=delete
```

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)