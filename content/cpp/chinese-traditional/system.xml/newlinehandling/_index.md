---
title: NewLineHandling
second_title: Aspose.Slides for C++ API 參考文件
description: 指定如何處理換行字元。
type: docs
weight: 690
url: /zh-hant/system.xml/newlinehandling/
---
## NewLineHandling 列舉

指定如何處理換行字元。

```cpp
enum class NewLineHandling
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Replace | 0 | 換行字元會被取代，以符合 [XmlWriterSettings::set_NewLineChars](../xmlwritersettings/set_newlinechars/) 值中指定的字元。 |
| Entitize | 1 | 換行字元會被實體化。此設定在輸出被正常化的 [XmlReader](../xmlreader/) 讀取時會保留所有字元。 |
| None | 2 | 換行字元保持不變。輸出與輸入相同。 |

## 另見

* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)