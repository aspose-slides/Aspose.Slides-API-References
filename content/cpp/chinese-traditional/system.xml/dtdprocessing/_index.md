---
title: DtdProcessing
second_title: Aspose.Slides C++ API 參考
description: 指定處理 DTD 的選項。DtdProcessing 列舉由 XmlReaderSettings 類別使用。
type: docs
weight: 638
url: /zh-hant/system.xml/dtdprocessing/
---
## DtdProcessing 列舉


指定處理 DTD 的選項。DtdProcessing 列舉由 [XmlReaderSettings](../xmlreadersettings/) 類別使用。

```cpp
enum class DtdProcessing
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Prohibit | 0 | 指定當遇到 DTD 時，會拋出 XmlException，並帶有說明 DTD 被禁止的訊息。這是預設行為。 |
| Ignore | 1 | 導致 DOCTYPE 元素被忽略。不會進行 DTD 處理，且 DTD/DOCTYPE 在輸出時遺失。 |
| Parse | 2 | 用於解析 DTD。 |

## 另請參閱

* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)