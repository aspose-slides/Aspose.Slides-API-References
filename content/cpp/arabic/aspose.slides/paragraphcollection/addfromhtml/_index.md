---
title: AddFromHtml()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يضيف النص من سلسلة HTML المحددة إلى المجموعة.
type: docs
weight: 157
url: /ar/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) طريقة

يضيف النص من سلسلة html المحددة إلى المجموعة.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | نص HTML. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

يضيف النص من سلسلة html المحددة إلى المجموعة.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | نص HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن رد النداء للمُحَلِّ الذي يحل عناوين URI ويجلب الكائنات المشار إليها. |
| uri | [System::String](../../../system/string/) | URI لإضافة مستند HTML. يُستخدم لحل الروابط النسبية. |
## ملاحظات

يمكن أن يؤدي تحديد المُحَلِّ إلى إحداث ثغرة محتملة. استخدمه بحذر.
## انظر أيضاً

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [ParagraphCollection](../)
* فئة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)