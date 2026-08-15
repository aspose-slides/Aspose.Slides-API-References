---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for C++ API 參考
description: 指定在 Markdown 匯出期間，如何處理重複的普通空格字元。
type: docs
weight: 937
url: /zh-hant/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces enum

指定在 Markdown 匯出期間，如何處理重複的普通空格字元。

```cpp
enum class HandleRepeatedSpaces
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 所有空格均保留為普通空格字元，未做任何變更。未套用任何轉換，且多個連續空格會原樣匯出。 |
| AlternateSpacesToNbsp | 1 | 將兩個或以上連續的普通空格序列轉換為普通空格字元與不換行空格實體（**&nbsp;**）交替。第一個空格始終保留為普通空格。 |
| MultipleSpacesToNbsp | 2 | 將兩個或以上連續的普通空格序列轉換為保留第一個空格為普通空格字元，並將其餘所有空格替換為不換行空格實體（**&nbsp;**）。 |

## 另請參閱

* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)