---
title: StringTrimming
second_title: Aspose.Slides for C++ API 參考文件
description: 指定在不符合版面形狀的字串上，應如何裁切字元。
type: docs
weight: 495
url: /zh-hant/system.drawing/stringtrimming/
---
## StringTrimming 列舉

指定在不符合版面形狀的字串上，應如何裁切字元。

```cpp
enum class StringTrimming
```

### 值

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 不裁切。 |
| Character | 1 | 裁切至最近的字元。 |
| Word | 2 | 裁切至最近的詞。 |
| EllipsisCharacter | 3 | 裁切至最近的字元，並在字串末尾插入省略號。 |
| EllipsisWord | 4 | 裁切至最近的詞，並在字串末尾插入省略號。 |
| EllipsisPath | 5 | 裁切後的行中部份會被移除並以省略號取代。盡可能保留行最後以斜線分隔的段落。 |

## 參見

* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)