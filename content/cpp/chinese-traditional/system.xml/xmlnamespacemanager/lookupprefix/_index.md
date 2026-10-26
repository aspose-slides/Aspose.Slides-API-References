---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API 參考
description: 尋找給定命名空間 URI 所宣告的前置詞。
type: docs
weight: 131
url: /zh-hant/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) 方法

尋找給定命名空間 URI 所宣告的前置詞。

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | 用於解析前置詞的命名空間。 |

### 返回值

符合的前置詞。若沒有對應的前置詞，該方法返回 [String::Empty](../../../system/string/empty/)。如果提供 null 值，則返回 **nullptr**。

## 另請參閱

* Class [String](../../../system/string/)
* Class [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)