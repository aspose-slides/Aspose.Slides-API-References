---
title: Create()
second_title: Aspose.Slides for C++ API Reference
description: Creates default RSA aglorithm implementation.
type: docs
weight: 183
url: /cpp/system.security.cryptography/rsa/create/
---
## RSA::Create() method


Creates default [RSA](../) aglorithm implementation.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) method


Creates default [RSA](../) algorithm implementation.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Must be \"System.Security.Cryptography.RSACryptoServiceProvider\". |

## RSA::Create(int32_t) method


Creates default [RSA](../) algorithm implementation with specifed key size.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | The key size, in bits. |

## RSA::Create(const RSAParameters\&) method


Creates default [RSA](../) algorithm implementation with specifed parameters.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | The parameters for the [RSA](../) algorithm. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSA](../)
* Class [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)