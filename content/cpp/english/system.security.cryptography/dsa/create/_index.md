---
title: Create()
second_title: Aspose.Slides for C++ API Reference
description: Creates default DSA aglorithm implementation.
type: docs
weight: 105
url: /system.security.cryptography/dsa/create/
---
## DSA::Create() method


Creates default [DSA](../) aglorithm implementation.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```


### Return Value

[DSA](../) algorithm object.

## DSA::Create(const String\&) method


Creates default [DSA](../) algorithm implementation.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Must be \"System.Security.Cryptography.DSACryptoServiceProvider\". |

### Return Value

[DSA](../) algorithm object.

## DSA::Create(int32_t) method


Creates default [DSA](../) algorithm implementation with specifed key size.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | The key size, in bits. |

## DSA::Create(const DSAParameters\&) method


Creates default [DSA](../) algorithm implementation with specifed parameters.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | The parameters for the [DSA](../) algorithm. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DSA](../)
* Class [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)