---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回為指定的命名空間 URI 宣告的前置詞。
type: docs
weight: 417
url: /zh-hant/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) method

傳回為指定的命名空間 URI 宣告的前置詞。

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | 用於解析前置詞的命名空間 URI。 |

### 回傳值

若有為指定的命名空間 URI 指派前置詞，則回傳包含該前置詞的 [String](../../../system/string/)；否則，若未指派前置詞，則回傳 [String::Empty](../../../system/string/empty/)。回傳的 [String](../../../system/string/) 會被原子化。

## 相關參考

* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)