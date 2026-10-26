---
title: Write()
second_title: مرجع API Aspose.Slides للغة C++
description: يكتب مصفوفة البايتات المحددة إلى الدفق.
type: docs
weight: 404
url: /ar/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) طريقة

يكتب مصفوفة البايتات المحددة إلى الدفق.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايتات للكتابة. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايتات المحددة إلى الدفق.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من 0 للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) طريقة

يكتب مصفوفة البايتات المحددة إلى الدفق.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | مصفوفة البايتات للكتابة. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايتات المحددة إلى الدفق.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من 0 للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [SslStream](../)
* مساحة اسم [System::Net::Security](../../)
* مكتبة [Aspose.Slides](../../../)