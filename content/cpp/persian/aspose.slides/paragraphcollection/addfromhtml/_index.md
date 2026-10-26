---
title: AddFromHtml()
second_title: مرجع API Aspose.Slides برای C++
description: متن را از رشته HTML مشخص‌شده به مجموعه اضافه می‌کند.
type: docs
weight: 157
url: /fa/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) متد

متن را از رشته HTML مشخص‌شده به مجموعه اضافه می‌کند.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن HTML. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) متد

متن را از رشته HTML مشخص‌شده به مجموعه اضافه می‌کند.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | شیء بازخوانی‌گر که URIها را حل می‌کند و اشیاء مرجع را دریافت می‌کند. |
| uri | [System::String](../../../system/string/) | URI برای افزودن سند HTML. برای حل لینک‌های نسبی استفاده می‌شود. |

## یادداشت‌ها

مشخص کردن resolver می‌تواند به‌طور بالقوه یک آسیب‌پذیری ایجاد کند. با احتیاط استفاده کنید.

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [ParagraphCollection](../)
* کلاس [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)