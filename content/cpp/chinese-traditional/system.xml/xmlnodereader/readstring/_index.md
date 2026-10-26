---
title: ReadString()
second_title: Aspose.Slides for C++ API 參考
description: 將元素或文字節點的內容讀取為字串。
type: docs
weight: 391
url: /zh-hant/system.xml/xmlnodereader/readstring/
---
## XmlNodeReader::ReadString() 方法

讀取元素或文字節點的內容作為字串。

```cpp
String System::Xml::XmlNodeReader::ReadString() override
```

### 傳回值

元素或類文字節點的內容（這可能包含 CDATA、[Text](../../../system.text/) 節點等）。如果讀取器的位置不在元素或文字節點上，或者在目前上下文中沒有更多文字內容可返回，則可能是空字串。注意：文字節點可以是元素或屬性文字節點。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlNodeReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)