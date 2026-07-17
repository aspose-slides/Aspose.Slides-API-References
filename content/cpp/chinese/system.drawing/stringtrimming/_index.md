---
title: StringTrimming
second_title: Aspose.Slides for C++ API 参考
description: 指定当字符串不符合布局形状时应如何修剪字符。
type: docs
weight: 495
url: /zh/system.drawing/stringtrimming/
---
## StringTrimming 枚举

指定当字符串不符合布局形状时应如何修剪字符。

```cpp
enum class StringTrimming
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 不进行修剪。 |
| Character | 1 | 修剪到最近的字符。 |
| Word | 2 | 修剪到最近的单词。 |
| EllipsisCharacter | 3 | 修剪到最近的字符并在字符串末尾插入省略号。 |
| EllipsisWord | 4 | 修剪到最近的单词并在字符串末尾插入省略号。 |
| EllipsisPath | 5 | 从修剪的行中移除中间部分并用省略号替代。尽可能保留该行最后一个以斜杠分隔的段落。 |

## 另请参阅

* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)