---
title: XmlParserContext()
second_title: Aspose.Slides for C++ API 參考
description: "使用指定的 XmlNameTable、XmlNamespaceManager、xml:lang 和 xml:space 值，初始化 XmlParserContext 類別的新執行個體。"
type: docs
weight: 261
url: /zh-hant/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) 建構函式

初始化一個新的 [XmlParserContext](../) 類別實例，使用指定的 [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、**xml:lang** 和 **xml:space** 值。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 用於原子化字串的 [XmlNameTable](../../xmlnametable/)。如果此值為 **nullptr**，則使用用於建構 **nsMgr** 的名稱表。欲取得有關原子化字串的更多資訊，請參閱 [XmlNameTable](../../xmlnametable/)。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 用於查找命名空間資訊的 [XmlNamespaceManager](../../xmlnamespacemanager/)，或 **nullptr**。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 範圍。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | 指示 **xml:space** 範圍的 XmlSpace 值。 |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) 建構函式

初始化一個新的 [XmlParserContext](../) 類別實例，使用指定的 [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、**xml:lang**、**xml:space** 與編碼。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 用於原子化字串的 [XmlNameTable](../../xmlnametable/)。如果此值為 **nullptr**，則使用用於建構 **nsMgr** 的名稱表。欲取得有關原子化字串的更多資訊，請參閱 [XmlNameTable](../../xmlnametable/)。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 用於查找命名空間資訊的 [XmlNamespaceManager](../../xmlnamespacemanager/)，或 **nullptr**。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 範圍。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | 指示 **xml:space** 範圍的 XmlSpace 值。 |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | 指示編碼設定的 Encoding 物件。 |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) 建構函式

初始化一個新的 [XmlParserContext](../) 類別實例，使用指定的 [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、基礎 URI、**xml:lang**、**xml:space** 與文件類型值。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 用於原子化字串的 [XmlNameTable](../../xmlnametable/)。如果此值為 **nullptr**，則使用用於建構 **nsMgr** 的名稱表。欲取得有關原子化字串的更多資訊，請參閱 [XmlNameTable](../../xmlnametable/)。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 用於查找命名空間資訊的 [XmlNamespaceManager](../../xmlnamespacemanager/)，或 **nullptr**。 |
| docTypeName | const [String](../../../system/string/)\& | 文件類型聲明的名稱。 |
| pubId | const [String](../../../system/string/)\& | 公用識別碼。 |
| sysId | const [String](../../../system/string/)\& | 系統識別碼。 |
| internalSubset | const [String](../../../system/string/)\& | 內部 DTD 子集。此 DTD 子集用於實體解析，而非文件驗證。 |
| baseURI | const [String](../../../system/string/)\& | XML 片段的基礎 URI（載入該片段的來源位置）。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 範圍。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | 指示 **xml:space** 範圍的 XmlSpace 值。 |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) 建構函式

初始化一個新的 [XmlParserContext](../) 類別實例，使用指定的 [XmlNameTable](../../xmlnametable/)、[XmlNamespaceManager](../../xmlnamespacemanager/)、基礎 URI、**xml:lang**、**xml:space**、編碼 與文件類型值。

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | 用於原子化字串的 [XmlNameTable](../../xmlnametable/)。如果此值為 **nullptr**，則使用用於建構 **nsMgr** 的名稱表。欲取得有關原子化字串的更多資訊，請參閱 [XmlNameTable](../../xmlnametable/)。 |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | 用於查找命名空間資訊的 [XmlNamespaceManager](../../xmlnamespacemanager/)，或 **nullptr**。 |
| docTypeName | const [String](../../../system/string/)\& | 文件類型聲明的名稱。 |
| pubId | const [String](../../../system/string/)\& | 公用識別碼。 |
| sysId | const [String](../../../system/string/)\& | 系統識別碼。 |
| internalSubset | const [String](../../../system/string/)\& | 內部 DTD 子集。此 DTD 用於實體解析，而非文件驗證。 |
| baseURI | const [String](../../../system/string/)\& | XML 片段的基礎 URI（載入該片段的來源位置）。 |
| xmlLang | const [String](../../../system/string/)\& | **xml:lang** 範圍。 |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | 指示 **xml:space** 範圍的 XmlSpace 值。 |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | 指示編碼設定的 Encoding 物件。 |

## 另請參閱

* 列舉 [XmlSpace](../../xmlspace/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNameTable](../../xmlnametable/)
* 類別 [XmlNamespaceManager](../../xmlnamespacemanager/)
* 類別 [String](../../../system/string/)
* 類別 [XmlParserContext](../)
* 類別 [Encoding](../../../system.text/encoding/)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)