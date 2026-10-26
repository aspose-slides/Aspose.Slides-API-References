---
title: AddFromHtml()
second_title: مرجع API Aspose.Slides للغة C++
description: يضيف نصًا من سلسلة HTML المحددة إلى المجموعة.
type: docs
weight: 92
url: /ar/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) طريقة

يضيف نصًا من سلسلة HTML المحددة إلى المجموعة.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```


### المعاملات

| معتل | نوع | وصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | نص HTML. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) طريقة

يضيف نصًا من سلسلة HTML المحددة إلى المجموعة.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### المعاملات

| معتل | نوع | وصف |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | نص HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | كائن استدعاء رد الاتصال الذي يحل عناوين URI ويجلب الكائنات المشار إليها. |
| uri | [System::String](../../../system/string/) | URI لإضافة مستند HTML. يُستخدم لحل الروابط النسبية. |
## ملاحظات

قد يؤدي تحديد الـ resolver إلى إمكانية وجود ثغرة أمنية. استخدمه بحذر.
## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [IParagraphCollection](../)
* فئة [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)