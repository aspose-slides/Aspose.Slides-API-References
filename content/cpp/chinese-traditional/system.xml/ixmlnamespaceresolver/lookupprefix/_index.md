---
title: LookupPrefix()
second_title: Aspose.Slides 的 C++ API 參考
description: 傳回映射至指定名稱空間 URI 的字首。
type: docs
weight: 27
url: /zh-hant/system.xml/ixmlnamespaceresolver/lookupprefix/
---
## IXmlNamespaceResolver::LookupPrefix(const String\&) 方法

傳回映射至指定名稱空間 URI 的字首。

```cpp
virtual String System::Xml::IXmlNamespaceResolver::LookupPrefix(const String &namespaceName)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceName | const [String](../../../system/string/)\& | 您想要查找其字首的名稱空間 URI。 |

### 傳回值

映射至該名稱空間 URI 的字首；若該名稱空間 URI 未映射至任何字首，則為 **nullptr**。

## 參見

* 類別 [String](../../../system/string/)
* 類別 [IXmlNamespaceResolver](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)