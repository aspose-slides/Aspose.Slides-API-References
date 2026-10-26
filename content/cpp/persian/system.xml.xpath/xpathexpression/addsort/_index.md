---
title: AddSort()
second_title: مرجع API Aspose.Slides برای C++
description: زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، گره‌های انتخاب‌شده توسط عبارت XPath را بر اساس شیء IComparer مشخص‌شده مرتب می‌کند.
type: docs
weight: 27
url: /fa/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) method

زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، گره‌های انتخاب‌شده توسط عبارت [XPath](../../) را بر اساس شیء IComparer مشخص‌شده مرتب می‌کند.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | شیئی که کلید مرتب‌سازی را نشان می‌دهد. این می‌تواند مقدار **string** گره باشد یا یک شیء [XPathExpression](../) با عبارت کامپایل‌شده [XPath](../../). |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | شیء IComparer که مقایسه‌های نوع داده خاص را برای مقایسه دو شیء جهت برابری فراهم می‌کند. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) method

زمانی که در یک کلاس مشتق‌شده بازنویسی می‌شود، گره‌های انتخاب‌شده توسط عبارت [XPath](../../) را بر اساس پارامترهای ارائه‌شده مرتب می‌کند.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | شیئی که کلید مرتب‌سازی را نشان می‌دهد. این می‌تواند مقدار **string** گره باشد یا یک شیء [XPathExpression](../) با عبارت کامپایل‌شده [XPath](../../). |
| order | [XmlSortOrder](../../xmlsortorder/) | مقدار XmlSortOrder که ترتیب مرتب‌سازی را نشان می‌دهد. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | مقدار XmlCaseOrder که نحوه مرتب‌سازی حروف بزرگ و کوچک را نشان می‌دهد. |
| lang | [String](../../../system/string/) | زبانی که برای مقایسه استفاده می‌شود. از کلاس [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) استفاده می‌کند که می‌تواند به متد [String::Compare](../../../system/string/compare/) برای انواع زبان پاس داده شود، برای مثال، "us-en" برای انگلیسی ایالات-متحده. اگر رشته‌ی خالی تعیین شود، محیط سیستم برای تعیین [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) استفاده می‌شود. |
| dataType | [XmlDataType](../../xmldatatype/) | مقدار XmlDataType که ترتیب مرتب‌سازی برای نوع داده را نشان می‌دهد. |

## مراجع

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [IComparer](../../../system.collections.generic/icomparer/)
* کلاس [XPathExpression](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml::XPath](../../)
* کتابخانه [Aspose.Slides](../../../)