---
title: Write()
second_title: Aspose.Slides لـ C++ مرجع API
description: يكتب النطاق الفرعي المحدد من البايتات من المصفوفة البايتية المحددة إلى الدفق.
type: docs
weight: 248
url: /ar/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة. |
| offset | **int32_t** | فهرس يبدأ من 0 للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة. |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

Writes the specified subrange of bytes from the specified byte array to the stream.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض المصفوفة الذي يحتوي على البايتات للكتابة. |
| offset | **int32_t** | فهرس يبدأ من 0 للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة. |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة. |

## انظر أيضًا

* تعريف النوع [ArrayPtr](../../../system/arrayptr/)
* فئة [FileStream](../)
* نطاق الأسماء [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)