---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 參考
description: 在衍生類別中覆寫時，解析當前元素範圍內的名稱空間前綴。
type: docs
weight: 729
url: /zh-hant/system.xml/xmlreader/lookupnamespace/
---
## XmlReader::LookupNamespace(const String\&) 方法

在衍生類別中覆寫時，會解析當前元素範圍內的名稱空間前綴。

```cpp
virtual String System::Xml::XmlReader::LookupNamespace(const String &prefix)=0
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 欲解析其名稱空間 URI 的前綴。若要匹配預設名稱空間，請傳遞空字串。 |

### 回傳值

前綴對應的名稱空間 URI，若未找到匹配的前綴則為 **nullptr**。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)