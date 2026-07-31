---
title: Append()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan karakter ke builder.
type: docs
weight: 118
url: /id/system.text/stringbuilder/append/
---
## StringBuilder::Append(char_t) metode

Menambahkan karakter ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | char_t | Nilai karakter. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(char_t, int) metode

Menambahkan karakter ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(char_t c, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | char_t | Nilai karakter. |
| count | int | Berapa kali mengulangi karakter yang dimasukkan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&) metode

Menambahkan array karakter ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Karakter untuk ditambahkan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(const ArrayPtr\<char_t\>\&, int, int) metode

Menambahkan potongan array karakter ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const ArrayPtr<char_t> &arr, int startIndex, int charCount)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Karakter untuk ditambahkan. |
| startIndex | int | Indeks awal potongan. |
| charCount | int | Panjang potongan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(const String\&) metode

Menambahkan string ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk ditambahkan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(const String\&, int, int) metode

Menambahkan potongan string ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const String &str, int startIndex, int charCount)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk ditambahkan. |
| startIndex | int | Indeks awal potongan. |
| charCount | int | Panjang potongan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(const SharedPtr\<T\>\&) metode

Menambahkan representasi string objek ke builder.

```cpp
template<class T> StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<T> &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Object](../../../system/object/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<T\>\& | [Object](../../../system/object/) untuk diserialisasi dan ditambahkan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(const SharedPtr\<StringBuilder\>\&) metode

Menambahkan konten builder ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(const SharedPtr<StringBuilder> &builder)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| builder | const [SharedPtr](../../../system/sharedptr/)\<[StringBuilder](../)\>\& | Builder untuk menambahkan konten darinya. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(float) metode

Menambahkan nilai floating point ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(float f)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| f | **float** | Nilai untuk diserialisasi dan ditambahkan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(double) metode

Menambahkan nilai floating point ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(double df)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| df | **double** | Nilai untuk diserialisasi dan ditambahkan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(int) metode

Menambahkan nilai integer ke builder.

```cpp
StringBuilder * System::Text::StringBuilder::Append(int i)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| i | int | Nilai untuk diserialisasi dan ditambahkan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(T) metode

Menambahkan nilai aritmetika ke builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Append(T value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe aritmetika. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T | Nilai untuk diserialisasi dan ditambahkan. |

### Nilai Kembali

Pointer ini.

## StringBuilder::Append(E) metode

Menambahkan representasi string nilai enum ke builder.

```cpp
template<class E> std::enable_if<std::is_enum<E>::value, StringBuilder *>::type System::Text::StringBuilder::Append(E e)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| E | [Enum](../../../system/enum/) tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| e | E | Nilai untuk diserialisasi dan ditambahkan. |

### Nilai Kembali

Pointer ini.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)