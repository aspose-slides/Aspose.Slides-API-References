---
title: XmlParserContext()
second_title: Aspose.Slides for C++ API 参考
description: "使用指定的 XmlNameTable、XmlNamespaceManager、xml:lang 和 xml:space 值初始化 XmlParserContext 类的新实例。"
type: docs
weight: 261
url: /zh/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) 构造函数

使用指定的 [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、**xml:lang** 和 **xml:space** 值初始化 [XmlParserContext](../) 类的新实例。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) 用于原子化字符串。如果此值为 **nullptr**，则使用用于构造 **nsMgr** 的名称表。有关原子化字符串的更多信息，请参阅 [XmlNameTable](../../xmlnametable/)。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) 用于查找命名空间信息，或 **nullptr**。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 范围。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | 表示 **xml:space** 范围的 XmlSpace 值。 |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) 构造函数

使用指定的 [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、**xml:lang**、**xml:space** 和编码初始化 [XmlParserContext](../) 类的新实例。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) 用于原子化字符串。如果此值为 **nullptr**，则使用用于构造 **nsMgr** 的名称表。有关原子化字符串的更多信息，请参阅 [XmlNameTable](../../xmlnametable/)。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) 用于查找命名空间信息，或 **nullptr**。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 范围。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | 表示 **xml:space** 范围的 XmlSpace 值。 |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | 指示编码设置的 Encoding 对象。 |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) 构造函数

使用指定的 [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、base URI、**xml:lang**、**xml:space** 和文档类型值初始化 [XmlParserContext](../) 类的新实例。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) 用于原子化字符串。如果此值为 **nullptr**，则使用用于构造 **nsMgr** 的名称表。有关原子化字符串的更多信息，请参阅 [XmlNameTable](../../xmlnametable/)。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) 用于查找命名空间信息，或 **nullptr**。 |
| docTypeName | const [String](../../../system/string/)\& | 文档类型声明的名称。 |
| pubId | const [String](../../../system/string/)\& | 公共标识符。 |
| sysId | const [String](../../../system/string/)\& | 系统标识符。 |
| internalSubset | const [String](../../../system/string/)\& | 内部 DTD 子集。该 DTD 子集用于实体解析，而非文档验证。 |
| baseURI | const [String](../../../system/string/)\& | XML 片段的基准 URI（加载片段的位置）。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 范围。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | 表示 **xml:space** 范围的 XmlSpace 值。 |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) 构造函数

使用指定的 [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、base URI、**xml:lang**、**xml:space**、编码和文档类型值初始化 [XmlParserContext](../) 类的新实例。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | [XmlNameTable](../../xmlnametable/) 用于原子化字符串。如果此值为 **nullptr**，则使用用于构造 **nsMgr** 的名称表。有关原子化字符串的更多信息，请参阅 [XmlNameTable](../../xmlnametable/)。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | [XmlNamespaceManager](../../xmlnamespacemanager/) 用于查找命名空间信息，或 **nullptr**。 |
| docTypeName | const [String](../../../system/string/)\& | 文档类型声明的名称。 |
| pubId | const [String](../../../system/string/)\& | 公共标识符。 |
| sysId | const [String](../../../system/string/)\& | 系统标识符。 |
| internalSubset | const [String](../../../system/string/)\& | 内部 DTD 子集。该 DTD 用于实体解析，而非文档验证。 |
| baseURI | const [String](../../../system/string/)\& | XML 片段的基准 URI（加载片段的位置）。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 范围。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | 表示 **xml:space** 范围的 XmlSpace 值。 |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | 指示编码设置的 Encoding 对象。 |

## 另请参阅

* 枚举 [XmlSpace](../../xmlspace/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNameTable](../../xmlnametable/)
* 类 [XmlNamespaceManager](../../xmlnamespacemanager/)
* 类 [String](../../../system/string/)
* 类 [XmlParserContext](../)
* 类 [Encoding](../../../system.text/encoding/)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)