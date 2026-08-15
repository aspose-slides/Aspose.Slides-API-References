---
title: GetNamespacesInScope()
second_title: Aspose.Slides C++ API 參考文件
description: 傳回包含目前作用域內所有命名空間的集合。
type: docs
weight: 716
url: /zh-hant/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) 方法


傳回包含目前作用域內所有命名空間的集合。

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 指定要傳回之命名空間節點類型的 XmlNamespaceScope 值。 |

### 返回值

包含目前作用域內所有命名空間的 IDictionary 物件。若讀取器未定位於元素，則傳回空的字典（無命名空間）。

## 另請參閱

* 列舉 [XmlNamespaceScope](../../xmlnamespacescope/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDictionary](../../../system.collections.generic/idictionary/)
* 類別 [String](../../../system/string/)
* 類別 [XmlTextReader](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)