---
title: ValidationType
second_title: Aspose.Slides for C++ API 參考文件
description: 指定要執行的驗證類型。
type: docs
weight: 729
url: /zh-hant/system.xml/validationtype/
---
## ValidationType 列舉

指定要執行的驗證類型。

```cpp
enum class ValidationType
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| None | 0 | 不執行任何驗證，也不會拋出驗證錯誤。此設定會建立符合 XML 1.0 的非驗證解析器。 |
| Auto | 1 | 如果找到 DTD 或結構描述資訊，則執行驗證。 |
| DTD | 2 | 根據 DTD 進行驗證。 |
| XDR | 3 | 根據 XML-Data Reduced (XDR) 綱要進行驗證，包含內嵌的 XDR 綱要。XDR 綱要會使用 **x-schema** 命名空間前置詞或 [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) 值來辨識。 |
| Schema | 4 | 根據 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 綱要進行驗證，包含內嵌的 XML 綱要。XML 綱要會透過 **schemaLocation** 屬性或提供的 **Schemas** 與命名空間 URI 相關聯。 |

## 另見

* Namespace [System::Xml](../)
* Library [Aspose.Slides](../../)