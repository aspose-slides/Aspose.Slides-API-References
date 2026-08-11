---
title: Read()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يقرأ البيانات من التيار.
type: docs
weight: 14
url: /ar/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


يقرأ البيانات من التيار.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مخزن بيانات الوجهة. |
| offset | **int32_t** | الإزاحة في مخزن الوجهة. |
| count | **int32_t** | عدد البايتات المراد قراءتها. |

### Return Value

عدد البايتات التي يتم قراءتها فعليًا.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


يقرأ البيانات من التيار.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | مخزن بيانات الوجهة. |
| offset | **int32_t** | الإزاحة في مخزن الوجهة. |
| count | **int32_t** | عدد البايتات المراد قراءتها. |

### Return Value

عدد البايتات التي يتم قراءتها فعليًا.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)