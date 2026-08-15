---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 參考
description: 傳回映射到指定前置字元的名稱空間 URI。
type: docs
weight: 14
url: /zh-hant/system.xml/ixmlnamespaceresolver/lookupnamespace/
---
## IXmlNamespaceResolver::LookupNamespace(const String\&) 方法

傳回映射到指定前置字元的名稱空間 URI。

```cpp
virtual String System::Xml::IXmlNamespaceResolver::LookupNamespace(const String &prefix)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 您想要尋找其名稱空間 URI 的前置字元。 |

### 回傳值

映射到前置字元的名稱空間 URI；如果前置字元未映射到名稱空間 URI，則為 **nullptr**。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [IXmlNamespaceResolver](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)