---
title: String()
second_title: Referensi API Aspose.Slides untuk C++
description: Konstruktor default. Membuat objek string yang dianggap null.
type: docs
weight: 14
url: /id/system/string/string/
---
## String::String() konstruktor

Konstruktor default. Membuat objek string yang dianggap null.

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) konstruktor

Membuat string berdasarkan literal string. Menganggap literal sebagai string yang diakhiri dengan null, menghitung panjang string target berdasarkan ukuran literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T\& | [String](../) pointer literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) konstruktor

Membuat string berdasarkan pointer string karakter. Menganggap string yang ditunjuk sebagai null-terminated, menghitung panjang string target berdasarkan karakter null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | Pointer string karakter. |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) konstruktor

Membuat string berdasarkan literal string. Menganggap literal sebagai string yang diakhiri dengan null dalam UTF-8, menghitung panjang string target berdasarkan ukuran literal.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T\& | [String](../) pointer literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) konstruktor

Membuat string berdasarkan pointer string karakter. Menganggap string yang ditunjuk sebagai null-terminated dalam UTF-8, menghitung panjang string target berdasarkan karakter null.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | Pointer string karakter. |

## String::String(const char16_t *, int) konstruktor

Membuat string dari pointer string karakter dan panjang eksplisit.

```cpp
System::String::String(const char16_t *str, int length)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointer, mungkin literal atau array. |
| length | int | Panjang string eksplisit |

## String::String(const ReadOnlySpan\<char16_t\>\&) konstruktor

Menginisialisasi instance baru dari kelas [System.String](../) dengan karakter Unicode yang ditunjukkan dalam span baca-saja yang ditentukan.

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | Span baca-saja karakter Unicode. |

## String::String(const char *, int) konstruktor

Membuat string dari pointer string karakter dan panjang eksplisit.

```cpp
System::String::String(const char *str, int length)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const char * | [String](../) pointer ke data UTF-8, mungkin literal atau array. |
| length | int | Panjang string eksplisit |

## String::String(const char16_t *, int, int) konstruktor

Membuat string dari pointer string karakter mulai dari posisi awal dengan panjang tertentu.

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const char16_t * | [String](../) pointer, mungkin literal atau array. |
| start | int | Posisi awal. |
| length | int | [String](../) panjang. |

## String::String(const char16_t, int) konstruktor

Konstruktor pengisian.

```cpp
System::String::String(const char16_t ch, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ch | const char16_t | Karakter pengisian. |
| count | int | Panjang target. |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) konstruktor

Konstruktor nullptr. Dideklarasikan sebagai template untuk menyelesaikan prioritas dengan konstruktor template lainnya.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Harus berupa nullptr_t |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) konstruktor

Membuat string berdasarkan literal widestring. Menganggap literal sebagai string yang diakhiri dengan null, menghitung panjang string target berdasarkan ukuran literal. Konversi dari **wchar_t** memakan waktu pada beberapa platform, sehingga konversi implisit tidak diizinkan.

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T\& | [String](../) pointer literal. |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) konstruktor

Membuat string berdasarkan pointer string lebar. Menganggap string yang ditunjuk sebagai null-terminated, menghitung panjang string target berdasarkan karakter null. Konversi dari **wchar_t** memakan waktu pada beberapa platform, sehingga konversi implisit tidak diizinkan.

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const T\& | Pointer string karakter. |

## String::String(const wchar_t *, int) konstruktor

Membuat string dari pointer string lebar dan panjang eksplisit. Konversi dari **wchar_t** memakan waktu pada beberapa platform, sehingga konversi implisit tidak diizinkan.

```cpp
System::String::String(const wchar_t *str, int length)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) pointer, mungkin literal atau array. |
| length | int | Panjang string eksplisit |

## String::String(const wchar_t, int) konstruktor

Konstruktor pengisian. Konversi dari **wchar_t** memakan waktu pada beberapa platform, sehingga konversi implisit tidak diizinkan.

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ch | const **wchar_t** | Karakter pengisian. |
| count | int | Panjang target. |

## String::String(const String\&) konstruktor

Konstruktor penyalinan.

```cpp
System::String::String(const String &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) untuk disalin. |

## String::String(String\&&) konstruktor

Konstruktor pemindahan.

```cpp
System::String::String(String &&str) noexcept
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) untuk memindahkan data dari. |

## String::String(const ArrayPtr\<char16_t\>\&) konstruktor

Mengonversi seluruh array karakter menjadi string.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) untuk dikonversi menjadi string. |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) konstruktor

Mengonversi sub-range array karakter menjadi string. Jika parameter berada di luar batas array, string kosong akan dibuat.

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Array karakter. |
| offset | int | Indeks mulai sub-array. |
| len | int | Panjang sub-array. |

## String::String(const codeporting_icu::UnicodeString\&) konstruktor

Membungkus UnicodeString ke dalam [String](../).

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString untuk dibungkus ke dalam [String](../). |

## String::String(codeporting_icu::UnicodeString\&&) konstruktor

Konstruktor pemindahan.

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString untuk dibungkus ke dalam [String](../). |

## String::String(const std::wstring\&) konstruktor

Membuat [String](../) dari widestring.

```cpp
System::String::String(const std::wstring &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const std::wstring\& | Widestring untuk dikonversi menjadi [String](../). |

## String::String(const std::u16string\&) konstruktor

Membuat [String](../) dari string utf16.

```cpp
System::String::String(const std::u16string &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const std::u16string\& | String Utf16 untuk dikonversi menjadi [String](../). |

## String::String(const std::string\&) konstruktor

Membuat [String](../) dari string std::string dalam format UTF-8.

```cpp
System::String::String(const std::string &utf8str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| utf8str | const std::string\& | String std::string untuk dikonversi menjadi [String](../). |

## String::String(const std::u32string\&) konstruktor

Membuat [String](../) dari string std::u32string.

```cpp
System::String::String(const std::u32string &u32str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| u32str | const std::u32string\& | String std::u32string untuk dikonversi menjadi [String](../). |

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)