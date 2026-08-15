---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 參考
description: 解析當前元素範圍內的命名空間前綴。
type: docs
weight: 612
url: /zh-hant/system.xml/xmltextreader/lookupnamespace/
---
## XmlTextReader::LookupNamespace(const String\&) 方法


解析當前元素範圍內的命名空間前綴。

```cpp
String System::Xml::XmlTextReader::LookupNamespace(const String &prefix) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 您想要解析其命名空間 URI 的前綴。若要匹配預設命名空間，請傳入空字串。此字串不必具備原子化。 |

### 返回值

前綴所映射的命名空間 URI；如果未找到匹配的前綴，則返回 **nullptr**。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)