---
title: Read()
second_title: Aspose.Slides لمرجع API C++
description: يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايت المحددة.
type: docs
weight: 391
url: /ar/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت التي تُكتب فيها البايتات المقروءة |
| offset | **int32_t** | موضع يبدأ من 0 في **buffer** لبدء الكتابة |
| count | **int32_t** | عدد البايتات التي يجب قراءتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | مصفوفة البايت التي تُكتب فيها البايتات المقروءة |
| offset | **int32_t** | موضع يبدأ من 0 في **buffer** لبدء الكتابة |
| count | **int32_t** | عدد البايتات التي يجب قرأتها |

### قيمة الإرجاع

عدد البايتات المقروءة

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)