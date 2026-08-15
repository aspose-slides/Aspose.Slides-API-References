---
title: GetExtensionObject()
second_title: Aspose.Slides C++ API 參考
description: 傳回與給定命名空間關聯的物件。
type: docs
weight: 27
url: /zh-hant/system.xml.xsl/xsltargumentlist/getextensionobject/
---
## XsltArgumentList::GetExtensionObject(const String\&) 方法

傳回與給定命名空間關聯的物件。

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetExtensionObject(const String &namespaceUri)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| namespaceUri | const [String](../../../system/string/)\& | 物件的命名空間 URI。 |

### 傳回值

命名空間 URI 物件，若未找到則為 **nullptr**。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)