---
title: Write()
second_title: Aspose.Slides لواجهة برمجة تطبيقات C++
description: يقوم بكتابة النطاق الفرعي المحدد من البايتات من المصفوفة المحددة إلى التدفق الأساسي.
type: docs
weight: 66
url: /ar/system.io/bufferedstream/write/
---
## طريقة BufferedStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method


يقوم بكتابة النطاق الفرعي المحدد من البايتات من المصفوفة المحددة إلى التدفق الأساسي.

```cpp
virtual void System::IO::BufferedStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## طريقة BufferedStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method


يقوم بكتابة النطاق الفرعي المحدد من البايتات من المصفوفة المحددة إلى التدفق الأساسي.

```cpp
virtual void System::IO::BufferedStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## انظر أيضاً

* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [BufferedStream](../)
* النطاق [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)