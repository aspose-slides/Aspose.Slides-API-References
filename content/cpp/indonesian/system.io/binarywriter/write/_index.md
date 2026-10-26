---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis nilai integer tak bertanda 8-bit yang ditentukan ke aliran output.
type: docs
weight: 92
url: /id/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) metode

Menulis nilai integer tak bertanda 8-bit yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **uint8_t** | Nilai yang akan ditulis |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) metode

Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte yang akan ditulis |
| index | int | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai |
| count | int | Jumlah elemen dalam subrentang yang akan ditulis; -1 menunjukkan bahwa subrentang berakhir pada akhir array **buffer** |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) metode

Menulis subrentang karakter UTF-16 yang ditentukan dari array karakter yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Array yang berisi karakter yang akan ditulis |
| index | int | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai |
| count | int | Jumlah karakter dalam subrentang yang akan ditulis; -1 menunjukkan bahwa subrentang berakhir pada akhir array **buffer** |

## BinaryWriter::Write(bool) metode

Menulis satu byte dengan nilai 0 jika **value** bernilai 'true' dan 1 jika **value** bernilai 'false' ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **bool** | Nilai boolean yang menentukan nilai byte yang akan ditulis ke aliran output |

## BinaryWriter::Write(char16_t) metode

Menulis nilai karakter 16-bit yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char16_t | Nilai yang akan ditulis |

## BinaryWriter::Write(int16_t) metode

Menulis nilai integer 16-bit yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **int16_t** | Nilai yang akan ditulis |

## BinaryWriter::Write(int) metode

Menulis nilai integer 32-bit yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int | Nilai yang akan ditulis |

## BinaryWriter::Write(int64_t) metode

Menulis nilai integer 64-bit yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **int64_t** | Nilai yang akan ditulis |

## BinaryWriter::Write(uint16_t) metode

Menulis nilai integer tak bertanda 16-bit yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **uint16_t** | Nilai yang akan ditulis |

## BinaryWriter::Write(uint32_t) metode

Menulis nilai integer tak bertanda 32-bit yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **uint32_t** | Nilai yang akan ditulis |

## BinaryWriter::Write(uint64_t) metode

Menulis nilai integer tak bertanda 64-bit yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **uint64_t** | Nilai yang akan ditulis |

## BinaryWriter::Write(float) metode

Menulis nilai titik mengambang presisi tunggal yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **float** | Nilai yang akan ditulis |

## BinaryWriter::Write(double) metode

Menulis nilai titik mengambang presisi ganda yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | **double** | Nilai yang akan ditulis |

## BinaryWriter::Write(const Decimal\&) metode

Menulis representasi byte dari nilai [Decimal](../../../system/decimal/) yang ditentukan ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | Nilai yang akan ditulis |

## BinaryWriter::Write(const String\&) metode

Menulis string berprefiks panjang dalam enkoding saat ini ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | String yang akan ditulis |

## BinaryWriter::Write(const char_t *) metode

Menulis string berprefiks panjang dalam enkoding saat ini ke aliran output.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const char_t * | C-string yang akan ditulis |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [BinaryWriter](../)
* Kelas [Decimal](../../../system/decimal/)
* Kelas [String](../../../system/string/)
* Ruang Nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)