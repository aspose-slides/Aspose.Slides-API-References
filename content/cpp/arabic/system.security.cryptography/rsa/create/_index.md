---
title: Create()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ تنفيذًا افتراضيًا لخوارزمية RSA.
type: docs
weight: 183
url: /ar/system.security.cryptography/rsa/create/
---
## RSA::Create() الطريقة

ينشئ تنفيذًا افتراضيًا لخوارزمية [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) الطريقة

ينشئ تنفيذًا افتراضيًا لخوارزمية [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | يجب أن يكون "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) الطريقة

ينشئ تنفيذًا افتراضيًا لخوارزمية [RSA](../) مع حجم المفتاح المحدد.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | حجم المفتاح، بالبتات. |

## RSA::Create(const RSAParameters\&) الطريقة

ينشئ تنفيذًا افتراضيًا لخوارزمية [RSA](../) مع المعلمات المحددة.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | المعلمات الخاصة بخوارزمية [RSA](../). |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSA](../)
* Class [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)