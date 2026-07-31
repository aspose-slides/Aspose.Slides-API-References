---
title: Create()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat implementasi algoritma ECDSA default.
type: docs
weight: 131
url: /id/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() metode

Membuat implementasi algoritma ECDSA default.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Nilai Kembalian

Objek algoritma ECDSA.

## ECDsa::Create(const ECCurve\&) metode

Membuat implementasi algoritma ECDSA default dengan kunci baru yang dibuat pada kurva yang ditentukan.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Kurva yang digunakan untuk pembuatan kunci. |

### Nilai Kembalian

Objek algoritma ECDSA.

## ECDsa::Create(const ECParameters\&) metode

Membuat implementasi algoritma ECDSA default menggunakan parameter yang ditentukan.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parameter yang merepresentasikan kunci. |

### Nilai Kembalian

Objek algoritma ECDSA.

## ECDsa::Create(const String\&) metode

Membuat implementasi algoritma ECDSA yang ditentukan.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Nama algoritma. |

### Nilai Kembalian

Objek algoritma ECDSA.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ECDsa](../)
* Kelas [String](../../../system/string/)
* Struct [ECCurve](../../eccurve/)
* Struct [ECParameters](../../ecparameters/)
* Ruang Nama [System::Security::Cryptography](../../)
* Perpustakaan [Aspose.Slides](../../../)