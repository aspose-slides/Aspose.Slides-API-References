---
title: XmlOutputMethod
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 指定用於序列化 XmlWriter 輸出的方式。
type: docs
weight: 846
url: /zh-hant/system.xml/xmloutputmethod/
---
## XmlOutputMethod 列舉

指定用於序列化 [XmlWriter](../xmlwriter/) 輸出的方式。

```cpp
enum class XmlOutputMethod
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| Xml | 0 | 根據 XML 1.0 規則序列化。 |
| Html | 1 | 根據 XSLT 所指定的 HTML 規則序列化。 |
| Text | 2 | 僅序列化文字區塊。 |
| AutoDetect | 3 | 在執行期間使用 XSLT 規則，在 [XmlOutputMethod::Xml](./) 與 [XmlOutputMethod::Html](./) 輸出方法之間做出選擇。 |

## 另見

* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)