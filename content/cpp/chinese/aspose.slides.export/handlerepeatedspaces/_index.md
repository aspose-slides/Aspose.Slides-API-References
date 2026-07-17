---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for C++ API 参考
description: 指定在 Markdown 导出期间如何处理重复的普通空格字符。
type: docs
weight: 937
url: /zh/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces 枚举

指定在 Markdown 导出期间如何处理重复的普通空格字符。

```cpp
enum class HandleRepeatedSpaces
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 所有空格都保留为普通空格字符，不做任何更改。未应用转换，多个连续空格将按原样导出。 |
| AlternateSpacesToNbsp | 1 | 将两个或更多连续普通空格的序列转换为普通空格字符和不间断空格实体（**&nbsp;**）交替出现。第一个空格始终保留为普通空格。 |
| MultipleSpacesToNbsp | 2 | 将两个或更多连续普通空格的序列转换为：保留第一个空格为普通空格字符，后续所有空格均替换为不间断空格实体（**&nbsp;**）。 |

## 另请参见

* 命名空间 [Aspose::Slides::Export](../)
* 库 [Aspose.Slides](../../)