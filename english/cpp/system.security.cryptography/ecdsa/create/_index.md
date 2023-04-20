---
title: Create()
second_title: Aspose.Slides for C++ API Reference
description: Creates default ECDSA aglorithm implementation.
type: docs
weight: 131
url: /cpp/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() method


Creates default ECDSA aglorithm implementation.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```


### Return Value

ECDSA algorithm object.

## ECDsa::Create(const ECCurve\&) method


Creates default ECDSA aglorithm implementation with newly created key over the specified curve.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curve to use for key creation. |

### Return Value

ECDSA algorithm object.

## ECDsa::Create(const ECParameters\&) method


Creates default ECDSA aglorithm implementation using the specified parameters.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parameters representing the key. |

### Return Value

ECDSA algorithm object.

## ECDsa::Create(const String\&) method


Creates specified ECDSA aglorithm implementation.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Algorithm name. |

### Return Value

ECDSA algorithm object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ECDsa](../)
* Class [String](../../../system/string/)
* Struct [ECCurve](../../eccurve/)
* Struct [ECParameters](../../ecparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)