---
title: Create()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan RSA algoritma uygulamasını oluşturur.
type: docs
weight: 183
url: /tr/system.security.cryptography/rsa/create/
---
## RSA::Create() metodu


Varsayılan [RSA](../) algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) metodu


Varsayılan [RSA](../) algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Şu olmalıdır: "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) metodu


Varsayılan [RSA](../) algoritma uygulamasını belirtilen anahtar boyutuyla oluşturur.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Anahtar boyutu, bit cinsinden. |

## RSA::Create(const RSAParameters\&) metodu


Varsayılan [RSA](../) algoritma uygulamasını belirtilen parametrelerle oluşturur.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | [RSA](../) algoritması için parametreler. |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [RSA](../)
* Sınıf [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Ad alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)