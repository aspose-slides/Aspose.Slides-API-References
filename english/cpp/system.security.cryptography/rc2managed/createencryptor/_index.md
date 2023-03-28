---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API Reference
description: Creates encryptor object with explicit parameters.
type: docs
weight: 1
url: /cpp/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>) method


Creates encryptor object with explicit parameters.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Encryption key in byte array form. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initial value in byte array form. |

### Return Value

Newly created encryptor object.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## RC2Managed::CreateEncryptor() method


Creates encryptor object with parameters defined by algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
## RC2Managed::CreateEncryptor([System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>) method


Creates encryptor object with parameters defined by algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)
