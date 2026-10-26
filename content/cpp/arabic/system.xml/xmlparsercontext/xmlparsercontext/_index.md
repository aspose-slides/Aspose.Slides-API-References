---
title: XmlParserContext()
second_title: Aspose.Slides لـ C++ مرجع API
description: "ينشئ نسخة جديدة من فئة XmlParserContext باستخدام القيم المحددة لـ XmlNameTable و XmlNamespaceManager و xml:lang و xml:space."
type: docs
weight: 261
url: /ar/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor

يُنشئ نسخةً جديدةً من الفئة [XmlParserContext](../) بالقيم المحددة [XmlNameTable](../../xmlnametable/)، [XmlNamespaceManager](../../xmlnamespacemanager/)، **xml:lang** و **xml:space**.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | ال[XmlNameTable](../../xmlnametable/) الذي يُستخدم لتجزئة السلاسل. إذا كان هذا **nullptr**، يُستَخدم جدول الأسماء المستخدم لإنشاء **nsMgr** بدلاً من ذلك. لمزيد من المعلومات حول السلاسل المجزأة، راجع [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | ال[XmlNamespaceManager](../../xmlnamespacemanager/) المُستخدم للبحث عن معلومات مساحة الاسم، أو **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | نطاق **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | قيمة XmlSpace تُشير إلى نطاق **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

يُنشئ نسخةً جديدةً من الفئة [XmlParserContext](../) باستخدام القيم المحددة [XmlNameTable](../../xmlnametable/)، [XmlNamespaceManager](../../xmlnamespacemanager/)، **xml:lang**، **xml:space**، والترميز.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | ال[XmlNameTable](../../xmlnametable/) المُستخدم لتجزئة السلاسل. إذا كان هذا **nullptr**، يُستَخدم جدول الأسماء المُستخدم لإنشاء **nsMgr** بدلاً من ذلك. لمزيد من المعلومات حول السلاسل المجزأة، راجع [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | ال[XmlNamespaceManager](../../xmlnamespacemanager/) المُستخدم للبحث عن معلومات مساحة الاسم، أو **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | نطاق **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | قيمة XmlSpace تُشير إلى نطاق **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | كائن Encoding يُشير إلى إعداد الترميز. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor

يُنشئ نسخةً جديدةً من الفئة [XmlParserContext](../) باستخدام القيم المحددة [XmlNameTable](../../xmlnametable/)، [XmlNamespaceManager](../../xmlnamespacemanager/)، URI الأساسي، **xml:lang**، **xml:space**، وقيم نوع المستند.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | ال[XmlNameTable](../../xmlnametable/) المُستخدم لتجزئة السلاسل. إذا كان هذا **nullptr**، يُستَخدم جدول الأسماء المُستخدم لإنشاء **nsMgr** بدلاً من ذلك. لمزيد من المعلومات حول السلاسل المجزأة، راجع [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | ال[XmlNamespaceManager](../../xmlnamespacemanager/) المُستخدم للبحث عن معلومات مساحة الاسم، أو **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | اسم إعلان نوع المستند. |
| pubId | const [String](../../../system/string/)\& | المعرف العام. |
| sysId | const [String](../../../system/string/)\& | معرف النظام. |
| internalSubset | const [String](../../../system/string/)\& | المجموعة الداخلية لـ DTD. تُستخدم مجموعة DTD الداخلية لحل الكيانات، وليس للتحقق من صحة المستند. |
| baseURI | const [String](../../../system/string/)\& | URI الأساسي لجزء XML (الموقع الذي تم تحميل الجزء منه). |
| xmlLang | const [String](../../../system/string/)\& | نطاق **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | قيمة XmlSpace تُشير إلى نطاق **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

يُنشئ نسخةً جديدةً من الفئة [XmlParserContext](../) باستخدام القيم المحددة [XmlNameTable](../../xmlnametable/)، [XmlNamespaceManager](../../xmlnamespacemanager/)، URI الأساسي، **xml:lang**، **xml:space**، الترميز، وقيم نوع المستند.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | ال[XmlNameTable](../../xmlnametable/) المُستخدم لتجزئة السلاسل. إذا كان هذا **nullptr**، يُستَخدم جدول الأسماء المُستخدم لإنشاء **nsMgr** بدلاً من ذلك. لمزيد من المعلومات حول السلاسل المجزأة، راجع [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | ال[XmlNamespaceManager](../../xmlnamespacemanager/) المُستخدم للبحث عن معلومات مساحة الاسم، أو **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | اسم إعلان نوع المستند. |
| pubId | const [String](../../../system/string/)\& | المعرف العام. |
| sysId | const [String](../../../system/string/)\& | معرف النظام. |
| internalSubset | const [String](../../../system/string/)\& | المجموعة الداخلية لـ DTD. تُستخدم مجموعة DTD لحل الكيانات، وليس للتحقق من صحة المستند. |
| baseURI | const [String](../../../system/string/)\& | URI الأساسي لجزء XML (الموقع الذي تم تحميل الجزء منه). |
| xmlLang | const [String](../../../system/string/)\& | نطاق **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | قيمة XmlSpace تُشير إلى نطاق **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | كائن Encoding يُشير إلى إعداد الترميز. |

## أنظر أيضًا

* تعداد [XmlSpace](../../xmlspace/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [XmlNameTable](../../xmlnametable/)
* فئة [XmlNamespaceManager](../../xmlnamespacemanager/)
* فئة [String](../../../system/string/)
* فئة [XmlParserContext](../)
* فئة [Encoding](../../../system.text/encoding/)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)