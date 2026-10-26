---
title: Create()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat implementasi algoritma DSA default.
type: docs
weight: 105
url: /id/system.security.cryptography/dsa/create/
---
## DSA::Create() metode

Membuat implementasi algoritma default [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Nilai Kembali

[DSA](../) objek algoritma.

## DSA::Create(const String\&) metode

Membuat implementasi algoritma default [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Must be "System.Security.Cryptography.DSACryptoServiceProvider". |

### Nilai Kembali

[DSA](../) objek algoritma.

## DSA::Create(int32_t) metode

Membuat implementasi algoritma default [DSA](../) dengan ukuran kunci yang ditentukan.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Ukuran kunci, dalam bit. |

## DSA::Create(const DSAParameters\&) metode

Membuat implementasi algoritma default [DSA](../) dengan parameter yang ditentukan.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Parameter untuk algoritma [DSA](../). |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [DSA](../)
* Kelas [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Ruang Nama [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)