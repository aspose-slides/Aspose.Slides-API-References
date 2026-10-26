---
title: Format()
second_title: Referensi API Aspose.Slides untuk C++
description: Memformat string dalam gaya C#.
type: docs
weight: 885
url: /id/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method

Memformat string dalam gaya C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| Args | Argumen untuk memformat string. |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format yang digunakan untuk mengonversi argumen menjadi string. |
| format | const [String](../)\& | String format. |
| args | const Args\&... | Argumen untuk memformat string. |

## String::Format(std::nullptr_t, const String\&, const Args\&...) method

Memformat string dalam gaya C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| Args | Argumen untuk memformat string. |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | std::nullptr_t | String format. |
| args | const [String](../)\& | Argumen untuk memformat string. |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method

Memformat string dalam gaya C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| Args | Argumen untuk memformat string. |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | std::nullptr_t | String format. |
| args | const char16_t(&) | Argumen untuk memformat string. |

## String::Format(const String\&, const Args\&...) method

Memformat string dalam gaya C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| Args | Argumen untuk memformat string. |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../)\& | String format. |
| args | const Args\&... | Argumen untuk memformat string. |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method

Memformat string dalam gaya C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### Template parameters

| Parameter | Deskripsi |
| --- | --- |
| T | Argumen untuk memformat string. |

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../)\& | String format. |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | Argumen untuk memformat string. |

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [String](../)
* Kelas [IFormatProvider](../../iformatprovider/)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)