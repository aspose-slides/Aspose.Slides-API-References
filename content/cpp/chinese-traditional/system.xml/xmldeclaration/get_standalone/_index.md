---
title: get_Standalone()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回 standalone 屬性的值。
type: docs
weight: 40
url: /zh-hant/system.xml/xmldeclaration/get_standalone/
---
## XmlDeclaration::get_Standalone() 方法

返回 standalone 屬性的值。

```cpp
String System::Xml::XmlDeclaration::get_Standalone()
```

### 回傳值

有效值為 **yes**，如果 XML 文件所需的所有實體宣告均包含在文件中；或 **no**，如果需要外部文件類型定義 (DTD)。如果 XML 宣告中未出現 standalone 屬性，則此方法傳回 [String::Empty](../../../system/string/empty/)。

## 另見

* 類別 [String](../../../system/string/)
* 類別 [XmlDeclaration](../)
* 命名空間 [System::Xml](../../)
* 程式庫 [Aspose.Slides](../../../)