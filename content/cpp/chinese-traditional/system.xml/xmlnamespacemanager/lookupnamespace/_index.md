---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 參考
description: 傳回指定前置詞的名稱空間 URI。
type: docs
weight: 118
url: /zh-hant/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) 方法

傳回指定前置詞的名稱空間 URI。

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 您想要解析其名稱空間 URI 的前置詞。若要匹配預設名稱空間，請傳入 [String::Empty](../../../system/string/empty/)。 |

### 返回值

如果有對應的名稱空間，則傳回 **prefix** 的名稱空間 URI；若無對應的名稱空間，則傳回 **nullptr**。返回的字串已原子化。欲取得有關原子化字串的更多資訊，請參閱 [XmlNameTable](../../xmlnametable/) 類別。

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [XmlNamespaceManager](../)
* 命名空間 [System::Xml](../../)
* 函式庫 [Aspose.Slides](../../../)