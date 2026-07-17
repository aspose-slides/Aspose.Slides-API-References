---
title: get_Standalone()
second_title: Aspose.Slides for C++ API 参考
description: 返回 standalone 属性的值。
type: docs
weight: 40
url: /zh/system.xml/xmldeclaration/get_standalone/
---
## XmlDeclaration::get_Standalone() 方法

返回 standalone 属性的值。

```cpp
String System::Xml::XmlDeclaration::get_Standalone()
```

### 返回值

有效值为 **yes**，表示 XML 文档所需的所有实体声明都包含在文档中；或 **no**，表示需要外部文档类型定义 (DTD)。如果 XML 声明中没有出现 standalone 属性，则此方法返回 [String::Empty](../../../system/string/empty/)。

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlDeclaration](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)