---
title: AddFromHtml()
second_title: Aspose.Slides برای مرجع API C++
description: متن را از رشته HTML مشخص به مجموعه اضافه می‌کند.
type: docs
weight: 92
url: /fa/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) متد


متن را از رشته HTML مشخص به مجموعه اضافه می‌کند.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن HTML. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد


متن را از رشته HTML مشخص به مجموعه اضافه می‌کند.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء callback Resolver که URIها را حل می‌کند و اشیاء ارجاع داده شده را دریافت می‌کند. |
| uri | [System::String](../../../system/string/) | URI برای افزودن سند HTML. برای حل پیوندهای نسبی استفاده می‌شود. |
## توضیحات

مشخص کردن resolver می‌تواند بالقوه یک آسیب‌پذیری ایجاد کند. با احتیاط استفاده کنید.
## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [IParagraphCollection](../)
* کلاس [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)