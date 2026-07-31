---
title: Insert()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyisipkan string ke posisi tetap builder.
type: docs
weight: 183
url: /id/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) metode

Menyisipkan string ke posisi tetap builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Posisi untuk menyisipkan karakter. |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk disisipkan. |

### Nilai Kembali

Penunjuk ini.

## StringBuilder::Insert(int32_t, const String\&, int32_t) metode

Menyisipkan string berulang ke posisi tetap builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Posisi untuk menyisipkan karakter. |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk disisipkan. |
| count | **int32_t** | Berapa kali mengulang string **value**. |

### Nilai Kembali

Penunjuk ini.

## StringBuilder::Insert(int, char_t) metode

Menyisipkan karakter ke posisi tetap builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Posisi untuk menyisipkan karakter. |
| ch | char_t | Karakter untuk disisipkan. |

### Nilai Kembali

Penunjuk ini.

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) metode

Menyisipkan karakter ke posisi tetap builder.

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Posisi untuk menyisipkan karakter. |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) untuk menyisipkan potongan dari. |
| startIndex | int | [Array](../../../system/array/) indeks awal potongan. |
| charCount | int | [Array](../../../system/array/) panjang potongan. |

### Nilai Kembali

Penunjuk ini.

## StringBuilder::Insert(int, T) metode

Menyisipkan nilai ke posisi tetap builder.

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Parameter | tipe. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Posisi untuk menyisipkan karakter. |
| value | T | Nilai untuk diformat dan disisipkan. |

### Nilai Kembali

Penunjuk ini.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [StringBuilder](../)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::Text](../../)
* Pustaka [Aspose.Slides](../../../)