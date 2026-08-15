---
title: ConformanceLevel
second_title: Aspose.Slides for C++ API 參考
description: 指定 XmlReader 和 XmlWriter 物件執行的輸入或輸出檢查量。
type: docs
weight: 625
url: /zh-hant/system.xml/conformancelevel/
---
## ConformanceLevel 列舉

指定 [XmlReader](../xmlreader/) 和 [XmlWriter](../xmlwriter/) 物件執行的輸入或輸出檢查量。

```cpp
enum class ConformanceLevel
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Auto | 0 | [XmlReader](../xmlreader/) 或 [XmlWriter](../xmlwriter/) 物件會自動偵測應執行文件層級或片段層級的檢查，並執行相應的檢查。如果您正包裝另一個 [XmlReader](../xmlreader/) 或 [XmlWriter](../xmlwriter/) 物件，外部物件不會執行任何額外的相容性檢查。相容性檢查由底層物件負責。 |
| Fragment | 1 | XML 資料是 [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities)，如 W3C 所定義。此相容性等級表示可能沒有根元素但仍符合良好結構的 XML 文件。此檢查層級確保正在讀取或寫入的串流可被任何處理器作為 [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) 使用。 |
| Document | 2 | XML 資料符合 W3C 定義的良好結構 [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) 規則。此檢查層級確保正在讀取或寫入的串流可被任何處理器作為 [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) 使用。 |

## 另見

* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)