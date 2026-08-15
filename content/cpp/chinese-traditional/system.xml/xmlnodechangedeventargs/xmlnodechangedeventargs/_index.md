---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides for C++ API 參考
description: 初始化 XmlNodeChangedEventArgs 類別的新實例。
type: docs
weight: 79
url: /zh-hant/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor

初始化 [XmlNodeChangedEventArgs](../) 類別的新實例。

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 產生事件的 [XmlNode](../../xmlnode/)。 |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 產生事件的 [XmlNode](../../xmlnode/) 的舊父級 [XmlNode](../../xmlnode/)。 |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | 產生事件的 [XmlNode](../../xmlnode/) 的新父級 [XmlNode](../../xmlnode/)。 |
| oldValue | const [String](../../../system/string/)\& | 產生事件的 [XmlNode](../../xmlnode/) 的舊值。 |
| newValue | const [String](../../../system/string/)\& | 產生事件的 [XmlNode](../../xmlnode/) 的新值。 |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | XmlNodeChangedAction。 |

## 另請參閱

* 列舉 [XmlNodeChangedAction](../../xmlnodechangedaction/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [XmlNode](../../xmlnode/)
* 類別 [String](../../../system/string/)
* 類別 [XmlNodeChangedEventArgs](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)