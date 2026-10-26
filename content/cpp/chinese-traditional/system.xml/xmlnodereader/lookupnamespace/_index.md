---
title: LookupNamespace()
second_title: Aspose.Slides C++ API 參考
description: 在當前元素的作用域中解析命名空間前綴。
type: docs
weight: 404
url: /zh-hant/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) 方法

解析當前元素作用域中的命名空間前綴。

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要解析其命名空間 URI 的前綴。若要匹配預設命名空間，傳入空字串。此字串不需要原子化。 |

### 返回值

前綴映射到的命名空間 URI，若未找到匹配的前綴則為 **nullptr**。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlNodeReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)