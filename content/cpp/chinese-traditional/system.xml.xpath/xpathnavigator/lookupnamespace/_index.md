---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回指定前置詞的命名空間 URI。
type: docs
weight: 404
url: /zh-hant/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String&) 方法

傳回指定前置詞的命名空間 URI。

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 您想要解析其命名空間 URI 的前置詞。若要匹配預設命名空間，請傳入 [String::Empty](../../../system/string/empty/)。 |

### 回傳值

包含指定命名空間前置詞所指派的命名空間 URI 的 [String](../../../system/string/)；如果未指派任何命名空間 URI 給指定的前置詞，則為 **nullptr**。返回的 [String](../../../system/string/) 為原子化的。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XPathNavigator](../)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)