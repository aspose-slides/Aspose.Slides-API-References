---
title: XmlParserContext()
second_title: Aspose.Slides for C++ API Reference
description: "Initializes a new instance of the XmlParserContext class with the specified XmlNameTable, XmlNamespaceManager, xml:lang, and xml:space values."
type: docs
weight: 261
url: /cpp/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\&, const [String](../../../system/string/)\&, [System::Xml::XmlSpace](../../xmlspace/)) constructor


Initializes a new instance of the [XmlParserContext](../) class with the specified [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, and **xml:space** values.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | The [XmlNameTable](../../xmlnametable/) to use to atomize strings. If this is **nullptr**, the name table used to construct the **nsMgr** is used instead. For more information about atomized strings, see [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | The [XmlNamespaceManager](../../xmlnamespacemanager/) to use for looking up namespace information, or **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | The **xml:lang** scope. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | An XmlSpace value indicating the **xml:space** scope. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlParserContext::XmlParserContext(const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\&, const [String](../../../system/string/)\&, [System::Xml::XmlSpace](../../xmlspace/), const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\&) constructor


Initializes a new instance of the [XmlParserContext](../) class with the specified [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space**, and encoding.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | The [XmlNameTable](../../xmlnametable/) to use to atomize strings. If this is **nullptr**, the name table used to construct the **nsMgr** is used instead. For more information on atomized strings, see [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | The [XmlNamespaceManager](../../xmlnamespacemanager/) to use for looking up namespace information, or **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | The **xml:lang** scope. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | An XmlSpace value indicating the **xml:space** scope. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | An Encoding object indicating the encoding setting. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlParserContext::XmlParserContext(const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, [System::Xml::XmlSpace](../../xmlspace/)) constructor


Initializes a new instance of the [XmlParserContext](../) class with the specified [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, and document type values.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | The [XmlNameTable](../../xmlnametable/) to use to atomize strings. If this is **nullptr**, the name table used to construct the **nsMgr** is used instead. For more information about atomized strings, see [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | The [XmlNamespaceManager](../../xmlnamespacemanager/) to use for looking up namespace information, or **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | The name of the document type declaration. |
| pubId | const [String](../../../system/string/)\& | The public identifier. |
| sysId | const [String](../../../system/string/)\& | The system identifier. |
| internalSubset | const [String](../../../system/string/)\& | The internal DTD subset. The DTD subset is used for entity resolution, not for document validation. |
| baseURI | const [String](../../../system/string/)\& | The base URI for the XML fragment (the location from which the fragment was loaded). |
| xmlLang | const [String](../../../system/string/)\& | The **xml:lang** scope. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | An XmlSpace value indicating the **xml:space** scope. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
## XmlParserContext::XmlParserContext(const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\&, const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, const [String](../../../system/string/)\&, [System::Xml::XmlSpace](../../xmlspace/), const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\&) constructor


Initializes a new instance of the [XmlParserContext](../) class with the specified [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), base URI, **xml:lang**, **xml:space**, encoding, and document type values.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | The [XmlNameTable](../../xmlnametable/) to use to atomize strings. If this is **nullptr**, the name table used to construct the **nsMgr** is used instead. For more information about atomized strings, see [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | The [XmlNamespaceManager](../../xmlnamespacemanager/) to use for looking up namespace information, or **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | The name of the document type declaration. |
| pubId | const [String](../../../system/string/)\& | The public identifier. |
| sysId | const [String](../../../system/string/)\& | The system identifier. |
| internalSubset | const [String](../../../system/string/)\& | The internal DTD subset. The DTD is used for entity resolution, not for document validation. |
| baseURI | const [String](../../../system/string/)\& | The base URI for the XML fragment (the location from which the fragment was loaded). |
| xmlLang | const [String](../../../system/string/)\& | The **xml:lang** scope. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | An XmlSpace value indicating the **xml:space** scope. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | An Encoding object indicating the encoding setting. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Enum [XmlSpace](../../xmlspace/)
* Class [Encoding](../../../system.text/encoding/)
* Class [XmlParserContext](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
