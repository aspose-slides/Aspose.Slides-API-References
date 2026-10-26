---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 參考
description: 解析當前元素範圍內的命名空間前綴。
type: docs
weight: 547
url: /zh-hant/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) 方法

解析當前元素作用域中的命名空間前綴。

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 要解析其命名空間統一資源識別符 (URI) 的前綴。若要匹配預設命名空間，請傳遞空字串。 |

### 返回值

前綴映射的命名空間 URI，若找不到相符的前綴則返回 **nullptr**。

## 參見

* 類別 [String](../../../system/string/)
* 類別 [XmlValidatingReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)