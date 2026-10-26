---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis karakter yang ditentukan ke aliran.
type: docs
weight: 40
url: /id/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) metode

Menulis karakter yang ditentukan ke aliran.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char_t | Nilai yang akan ditulis |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metode

Menulis subrentang karakter yang ditentukan dari larik karakter yang ditentukan ke aliran.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Larik yang berisi karakter yang akan ditulis |
| index | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai |
| count | **int32_t** | Jumlah karakter dalam subrentang yang akan ditulis |

## StringWriter::Write(const String\&) metode

Menulis string yang ditentukan ke aliran.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | String yang akan ditulis |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [StringWriter](../)
* Kelas [String](../../../system/string/)
* Ruang nama [System::IO](../../)
* Library [Aspose.Slides](../../../)