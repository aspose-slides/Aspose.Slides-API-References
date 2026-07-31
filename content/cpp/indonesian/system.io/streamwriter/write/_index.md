---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis karakter yang ditentukan ke stream.
type: docs
weight: 79
url: /id/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) metode


Menulis karakter yang ditentukan ke stream.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char_t | Karakter yang akan ditulis |

## StreamWriter::Write(const String\&) metode


Menulis string yang ditentukan ke stream.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | String yang akan ditulis |

## StreamWriter::Write(const SharedPtr\<Object\>\&) metode


Menulis representasi string dari objek yang ditentukan ke stream.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objek yang akan ditulis |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) metode


Menulis semua karakter dari array yang ditentukan ke stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Array yang berisi karakter yang akan ditulis |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metode


Menulis subrentang UTF-16 karakter yang ditentukan dari array karakter yang ditentukan ke stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Array yang berisi karakter yang akan ditulis |
| index | **int32_t** | Indeks berbasis-0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai |
| count | **int32_t** | Jumlah karakter dalam subrentang yang akan ditulis; -1 menunjukkan bahwa subrentang berakhir di akhir array **buffer** |

## StreamWriter::Write(const char_t *) metode


Menulis c-string yang ditentukan ke stream.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const char_t * | c-string yang akan ditulis |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) metode


Menulis representasi string dari objek yang ditentukan ke stream.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Objek yang akan ditulis |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)