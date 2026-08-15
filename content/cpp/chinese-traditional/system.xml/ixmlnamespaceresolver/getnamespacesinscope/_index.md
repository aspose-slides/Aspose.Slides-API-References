---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回目前範圍內已定義的前置字元與名稱空間對映的集合。
type: docs
weight: 1
url: /zh-hant/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) 方法


傳回目前範圍內已定義的前置字元與名稱空間對映的集合。

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 指定要傳回之名稱空間節點類型的 XmlNamespaceScope 值。 |

### 傳回值

包含目前範圍內名稱空間的 IDictionary 集合。

## 另請參閱

* Enum [XmlNamespaceScope](../../xmlnamespacescope/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IDictionary](../../../system.collections.generic/idictionary/)
* 類別 [String](../../../system/string/)
* 類別 [IXmlNamespaceResolver](../)
* 命名空間 [System::Xml](../../)
* Library [Aspose.Slides](../../../)