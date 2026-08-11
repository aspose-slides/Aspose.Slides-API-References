---
title: XmlParserContext()
second_title: Aspose.Slides برای C++ مرجع API
description: "یک نمونه جدید از کلاس XmlParserContext را با مقادیر XmlNameTable، XmlNamespaceManager، xml:lang و xml:space مشخص‌شده مقداردهی اولیه می‌کند."
type: docs
weight: 261
url: /fa/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) سازنده

یک نمونه جدید از کلاس [XmlParserContext](../) را با مقادیر [XmlNameTable](../../xmlnametable/)، [XmlNamespaceManager](../../xmlnamespacemanager/)، **xml:lang** و **xml:space** مشخص‌شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) برای اتمی‌سازی رشته‌ها استفاده می‌شود. اگر این مقدار **nullptr** باشد، جدول نامی که برای ساخت **nsMgr** استفاده شده است به‌جای آن به‌کار گرفته می‌شود. برای اطلاعات بیشتر درباره رشته‌های اتمی‌سازی‌شده، به [XmlNameTable](../../xmlnametable/) مراجعه کنید. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) برای جستجوی اطلاعات فضای‌نام استفاده می‌شود، یا **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | دامنه **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | مقدار XmlSpace که دامنه **xml:space** را نشان می‌دهد. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) سازنده

یک نمونه جدید از کلاس [XmlParserContext](../) را با مقادیر [XmlNameTable](../../xmlnametable/)، [XmlNamespaceManager](../../xmlnamespacemanager/)، **xml:lang**، **xml:space** و رمزگذاری مشخص‌شده مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) برای اتمی‌سازی رشته‌ها استفاده می‌شود. اگر این مقدار **nullptr** باشد، جدول نامی که برای ساخت **nsMgr** استفاده شده است به‌جای آن به‌کار گرفته می‌شود. برای اطلاعات بیشتر درباره رشته‌های اتمی‌سازی‌شده، به [XmlNameTable](../../xmlnametable/) مراجعه کنید. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) برای جستجوی اطلاعات فضای‌نام استفاده می‌شود، یا **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | دامنه **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | مقدار XmlSpace که دامنه **xml:space** را نشان می‌دهد. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | یک شیء Encoding که تنظیمات رمزگذاری را نشان می‌دهد. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) سازنده

یک نمونه جدید از کلاس [XmlParserContext](../) را با مقادیر [XmlNameTable](../../xmlnametable/)، [XmlNamespaceManager](../../xmlnamespacemanager/)، URI پایه، **xml:lang**، **xml:space** و مقادیر نوع سند مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) برای اتمی‌سازی رشته‌ها استفاده می‌شود. اگر این مقدار **nullptr** باشد، جدول نامی که برای ساخت **nsMgr** استفاده شده است به‌جای آن به‌کار گرفته می‌شود. برای اطلاعات بیشتر درباره رشته‌های اتمی‌سازی‌شده، به [XmlNameTable](../../xmlnametable/) مراجعه کنید. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) برای جستجوی اطلاعات فضای‌نام استفاده می‌شود، یا **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | نام اعلامیه نوع سند. |
| pubId | const [String](../../../system/string/)\& | شناسه عمومی. |
| sysId | const [String](../../../system/string/)\& | شناسه سیستم. |
| internalSubset | const [String](../../../system/string/)\& | زیرمجموعه داخلی DTD. زیرمجموعه DTD برای حل مراجع موجود استفاده می‌شود، نه برای اعتبارسنجی سند. |
| baseURI | const [String](../../../system/string/)\& | URI پایه برای بخش XML (محل بارگذاری بخش). |
| xmlLang | const [String](../../../system/string/)\& | دامنه **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | مقدار XmlSpace که دامنه **xml:space** را نشان می‌دهد. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) سازنده

یک نمونه جدید از کلاس [XmlParserContext](../) را با مقادیر [XmlNameTable](../../xmlnametable/)، [XmlNamespaceManager](../../xmlnamespacemanager/)، URI پایه، **xml:lang**، **xml:space**، رمزگذاری و مقادیر نوع سند مقداردهی اولیه می‌کند.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) برای اتمی‌سازی رشته‌ها استفاده می‌شود. اگر این مقدار **nullptr** باشد، جدول نامی که برای ساخت **nsMgr** استفاده شده است به‌جای آن به‌کار گرفته می‌شود. برای اطلاعات بیشتر درباره رشته‌های اتمی‌سازی‌شده، به [XmlNameTable](../../xmlnametable/) مراجعه کنید. |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) برای جستجوی اطلاعات فضای‌نام استفاده می‌شود، یا **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | نام اعلامیه نوع سند. |
| pubId | const [String](../../../system/string/)\& | شناسه عمومی. |
| sysId | const [String](../../../system/string/)\& | شناسه سیستم. |
| internalSubset | const [String](../../../system/string/)\& | زیرمجموعه داخلی DTD. DTD برای حل مراجع موجود استفاده می‌شود، نه برای اعتبارسنجی سند. |
| baseURI | const [String](../../../system/string/)\& | URI پایه برای بخش XML (محل بارگذاری بخش). |
| xmlLang | const [String](../../../system/string/)\& | دامنه **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | مقدار XmlSpace که دامنه **xml:space** را نشان می‌دهد. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | یک شیء Encoding که تنظیمات رمزگذاری را نشان می‌دهد. |

## مراجع دیگر

* عدد [XmlSpace](../../xmlspace/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNameTable](../../xmlnametable/)
* کلاس [XmlNamespaceManager](../../xmlnamespacemanager/)
* کلاس [String](../../../system/string/)
* کلاس [XmlParserContext](../)
* کلاس [Encoding](../../../system.text/encoding/)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)