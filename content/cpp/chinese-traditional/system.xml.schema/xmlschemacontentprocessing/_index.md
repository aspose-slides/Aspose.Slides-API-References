---
title: XmlSchemaContentProcessing
second_title: Aspose.Slides C++ API 參考文件
description: 提供有關 any 和 anyAttribute 元素取代之驗證模式的資訊。
type: docs
weight: 976
url: /zh-hant/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

提供有關 **any** 和 **anyAttribute** 元素取代的驗證模式資訊。

```cpp
enum class XmlSchemaContentProcessing
```

### 值

| 名稱 | 數值 | 說明 |
| --- | --- | --- |
| None | 0 | 文件項目未經驗證。 |
| Skip | 1 | 文件項目必須是符合 XML 語法的且不會被結構描述檔驗證。 |
| Lax | 2 | 如果找到關聯的結構描述檔，則會驗證文件項目。否則不會拋出錯誤。 |
| Strict | 3 | 結構描述檔處理器必須找到與指示的命名空間相關聯的結構描述檔，以驗證文件項目。 |

## 參見

* 命名空間 [System::Xml::Schema](../)
* 函式庫 [Aspose.Slides](../../)