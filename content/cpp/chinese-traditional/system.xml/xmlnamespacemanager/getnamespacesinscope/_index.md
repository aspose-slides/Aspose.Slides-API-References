---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 參考
description: 返回一個以前置詞為鍵的名稱空間名稱集合，可用於列舉目前作用域中的名稱空間。
type: docs
weight: 105
url: /zh-hant/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) 方法

傳回一個以前置詞為鍵的名稱空間名稱集合，可用於列舉目前作用域中的名稱空間。

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 指定要傳回的名稱空間節點類型的列舉值。 |

### 傳回值

目前作用域中的名稱空間與前置詞配對集合。

## 另請參閱

* 列舉 [XmlNamespaceScope](../../xmlnamespacescope/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDictionary](../../../system.collections.generic/idictionary/)
* 類別 [String](../../../system/string/)
* 類別 [XmlNamespaceManager](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)