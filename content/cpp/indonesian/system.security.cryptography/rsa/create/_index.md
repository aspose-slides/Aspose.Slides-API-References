---
title: Create()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat implementasi algoritma RSA default.
type: docs
weight: 183
url: /id/system.security.cryptography/rsa/create/
---
## RSA::Create() metode


Membuat implementasi algoritma default [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) metode


Membuat implementasi algoritma default [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Harus \"System.Security.Cryptography.RSACryptoServiceProvider\". |

## RSA::Create(int32_t) metode


Membuat implementasi algoritma default [RSA](../) dengan ukuran kunci yang ditentukan.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Ukuran kunci, dalam bit. |

## RSA::Create(const RSAParameters\&) metode


Membuat implementasi algoritma default [RSA](../) dengan parameter yang ditentukan.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | Parameter untuk algoritma [RSA](../).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [RSA](../)
* Kelas [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)