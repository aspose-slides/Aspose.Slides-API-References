---
title: FoundResult()
second_title: مرجع API Aspose.Slides للغة C++
description: طريقة رد نداء تستقبل البيانات حول النص الموجود.
type: docs
weight: 1
url: /ar/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) method

طريقة رد نداء تستقبل بيانات حول النص الموجود.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | الـ[ITextFrame](../../itextframe/) التي تم العثور على النص فيها. |
| sourceText | [System::String](../../../system/string/) | النص المصدر الذي تم العثور على النص فيه. |
| foundText | [System::String](../../../system/string/) | النص الموجود. |
| textPosition | **int32_t** | موضع النص الموجود. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ITextFrame](../../itextframe/)
* فئة [String](../../../system/string/)
* فئة [IFindResultCallback](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)