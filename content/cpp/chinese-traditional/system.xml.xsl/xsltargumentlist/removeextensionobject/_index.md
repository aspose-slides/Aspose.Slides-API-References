---
title: RemoveExtensionObject()
second_title: Aspose.Slides for C++ API 參考手冊
description: 從 XsltArgumentList 中移除具有命名空間 URI 的物件。
type: docs
weight: 79
url: /zh-hant/system.xml.xsl/xsltargumentlist/removeextensionobject/
---
## XsltArgumentList::RemoveExtensionObject(const String\&) 方法

從 [XsltArgumentList](../) 中移除具有命名空間 URI 的物件。

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveExtensionObject(const String &namespaceUri)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| namespaceUri | const [String](../../../system/string/)\& | 與要移除之物件相關聯的命名空間 URI。 |

### 回傳值

具有該命名空間 URI 的物件，若未找到則為 **nullptr**。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)