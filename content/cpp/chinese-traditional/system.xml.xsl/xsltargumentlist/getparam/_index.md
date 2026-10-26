---
title: GetParam()
second_title: Aspose.Slides for C++ API 參考
description: 傳回與具名空間限定名稱相關聯的參數。
type: docs
weight: 14
url: /zh-hant/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) 方法

返回與具名空間限定名稱相關聯的參數。

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 參數的名稱。[XsltArgumentList](../) 不會檢查傳入的名稱是否為有效的本地名稱；然而，名稱不能為 **nullptr**。 |
| namespaceUri | const [String](../../../system/string/)\& | 與參數相關聯的命名空間 URI。 |

### 返回值

參數物件；如果未找到則返回 **nullptr**。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XsltArgumentList](../)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)