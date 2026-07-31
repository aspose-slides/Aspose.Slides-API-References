---
title: Guid()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek yang mewakili GUID yang terdiri dari semua nol.
type: docs
weight: 1
url: /id/system/guid/guid/
---
## Guid::Guid() konstruktor

Membuat objek yang mewakili GUID yang terdiri dari semua nol.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) konstruktor

Membuat objek yang mewakili GUID yang ditentukan sebagai larik nilai bilangan bulat tak bertanda 8-bit.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | A byte-array containing separate bytes of the GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) konstruktor

Membuat objek yang mewakili GUID yang ditentukan sebagai tampilan larik nilai bilangan bulat tak bertanda 8-bit.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | A byte-array containing separate bytes of the GUID |

## Guid::Guid(const String\&) konstruktor

Membuat objek yang mewakili GUID yang ditentukan sebagai string.

```cpp
System::Guid::Guid(const String &g)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| g | const [String](../../string/)\& | The string representation of a GUID to be represented by the object being constructed |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) konstruktor

Membuat sebuah instance dari kelas [Guid](../) dari komponen GUID yang ditentukan.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 of the GUID |
| b | **int16_t** | Bits 32-47 of the GUID |
| c | **int16_t** | Bits 48-63 of the GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | A byte array containing bits 64-127 of the GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) konstruktor

Membuat sebuah instance dari kelas [Guid](../) dari komponen GUID yang ditentukan.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 of the GUID |
| b | **int16_t** | Bits 32-47 of the GUID |
| c | **int16_t** | Bits 48-63 of the GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | A byte array view containing bits 64-127 of the GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor

Membuat sebuah instance dari kelas [Guid](../) dari bilangan bulat tak bertanda dan byte yang ditentukan.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | **int32_t** | Bits 0-31 of the GUID |
| b | **int16_t** | Bits 32-47 of the GUID |
| c | **int16_t** | Bits 48-63 of the GUID |
| d | **uint8_t** | Bits 64-71 of the GUID |
| e | **uint8_t** | Bits 72-79 of the GUID |
| f | **uint8_t** | Bits 80-87 of the GUID |
| g | **uint8_t** | Bits 88-95 of the GUID |
| h | **uint8_t** | Bits 96-103 of the GUID |
| i | **uint8_t** | Bits 104-111 of the GUID |
| j | **uint8_t** | Bits 112-119 of the GUID |
| k | **uint8_t** | Bits 120-127 of the GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) konstruktor

Membuat sebuah instance dari kelas [Guid](../) dari bilangan bulat tak bertanda dan byte yang ditentukan.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | **uint32_t** | Bits 0-31 of the GUID |
| b | **uint16_t** | Bits 32-47 of the GUID |
| c | **uint16_t** | Bits 48-63 of the GUID |
| d | **uint8_t** | Bits 64-71 of the GUID |
| e | **uint8_t** | Bits 72-79 of the GUID |
| f | **uint8_t** | Bits 80-87 of the GUID |
| g | **uint8_t** | Bits 88-95 of the GUID |
| h | **uint8_t** | Bits 96-103 of the GUID |
| i | **uint8_t** | Bits 104-111 of the GUID |
| j | **uint8_t** | Bits 112-119 of the GUID |
| k | **uint8_t** | Bits 120-127 of the GUID |

## Guid::Guid(const Guid\&) konstruktor

Membuat objek yang mewakili GUID yang sama dengan objek yang ditentukan.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| guid | const [Guid](../)\& | Objek [Guid](../) untuk menyalin nilai GUID dari |

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [Guid](../)
* Kelas [String](../../string/)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)