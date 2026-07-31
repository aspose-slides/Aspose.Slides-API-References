---
title: WriteLine()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis karakter terminator baris ke aliran.
type: docs
weight: 92
url: /id/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() metode

Menulis karakter terminator baris ke aliran.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) metode

Menulis string yang ditentukan diikuti oleh karakter terminasi baris ke aliran.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | String yang akan ditulis |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) metode

Menulis representasi string dari objek yang ditentukan diikuti oleh karakter terminasi baris ke aliran.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objek yang akan ditulis |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) metode

Menulis semua karakter dari array yang ditentukan diikuti oleh karakter terminasi baris ke aliran.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Array yang berisi karakter yang akan ditulis |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metode

Menulis subrentang UTF-16 karakter yang ditentukan dari array karakter yang ditentukan diikuti oleh karakter terminasi baris ke aliran.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Array yang berisi karakter yang akan ditulis |
| index | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai |
| count | **int32_t** | Jumlah karakter dalam subrentang yang akan ditulis; -1 menunjukkan bahwa subrentang berakhir di mana array **buffer** berakhir |

## StreamWriter::WriteLine(const char_t *) metode

Menulis c-string yang ditentukan diikuti oleh karakter terminasi baris ke aliran.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const char_t * | c-string yang akan ditulis |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) metode

Menulis representasi string dari objek yang ditentukan diikuti oleh karakter terminasi baris ke aliran.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
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
* Kelas [StreamWriter](../)
* Kelas [String](../../../system/string/)
* Kelas [Object](../../../system/object/)
* Ruang nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)