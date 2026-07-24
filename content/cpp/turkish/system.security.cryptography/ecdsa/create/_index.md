---
title: Create()
second_title: Aspose.Slides for C++ API Referansı
description: Varsayılan ECDSA algoritma uygulamasını oluşturur.
type: docs
weight: 131
url: /tr/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() method

Varsayılan ECDSA algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Dönüş Değeri

ECDSA algorithm object.

## ECDsa::Create(const ECCurve\&) method

Belirtilen eğri üzerinde yeni oluşturulan anahtar ile varsayılan ECDSA algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Anahtar oluşturma için kullanılacak eğri. |

### Dönüş Değeri

ECDSA algorithm object.

## ECDsa::Create(const ECParameters\&) method

Belirtilen parametreleri kullanarak varsayılan ECDSA algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Anahtarı temsil eden parametreler. |

### Dönüş Değeri

ECDSA algorithm object.

## ECDsa::Create(const String\&) method

Belirtilen ECDSA algoritma uygulamasını oluşturur.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Algoritma adı. |

### Dönüş Değeri

ECDSA algorithm object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ECDsa](../)
* Class [String](../../../system/string/)
* Struct [ECCurve](../../eccurve/)
* Struct [ECParameters](../../ecparameters/)
* İsim Alanı [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)