---
title: Create()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan DSA algoritması uygulamasını oluşturur.
type: docs
weight: 105
url: /tr/system.security.cryptography/dsa/create/
---
## DSA::Create() yöntemi

Varsayılan [DSA](../) algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Dönüş Değeri

[DSA](../) algoritma nesnesi.

## DSA::Create(const String\&) yöntemi

Varsayılan [DSA](../) algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Şu olmalıdır "System.Security.Cryptography.DSACryptoServiceProvider". |

### Dönüş Değeri

[DSA](../) algoritma nesnesi.

## DSA::Create(int32_t) yöntemi

Belirtilen anahtar boyutuyla varsayılan [DSA](../) algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Anahtar boyutu, bit cinsinden. |

## DSA::Create(const DSAParameters\&) yöntemi

Belirtilen parametrelerle varsayılan [DSA](../) algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | [DSA](../) algoritması için parametreler. |

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [DSA](../)
* Sınıf [String](../../../system/string/)
* Yapı [DSAParameters](../../dsaparameters/)
* Ad Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)