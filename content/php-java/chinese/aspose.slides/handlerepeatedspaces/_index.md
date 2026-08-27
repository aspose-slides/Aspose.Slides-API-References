---
title: HandleRepeatedSpaces
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/handlerepeatedspaces/
---
## HandleRepeatedSpaces 类

指定在 Markdown 导出期间如何处理重复的普通空格字符。

## 常量

| Name | Value | Description |
| --- | --- | --- |
[None](#None) | 0 | 所有空格都保留为普通空格字符，不做任何更改。未应用转换，多个连续空格将原样导出。 |
[AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | 1 | 将两个或更多连续普通空格的序列转换为交替使用普通空格字符和不间断空格实体 NBSP。第一个空格始终保留为普通空格。 |
[MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | 2 | 将两个或更多连续普通空格的序列转换为保留第一个空格为普通空格字符，并将所有后续空格替换为不间断空格实体 NBSP。 |

---

### None {#None}
所有空格都保留为普通空格字符，不做任何更改。未应用转换，多个连续空格将原样导出。

---

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
将两个或更多连续普通空格的序列转换为交替使用普通空格字符和不间断空格实体 NBSP。第一个空格始终保留为普通空格。

---

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
将两个或更多连续普通空格的序列转换为保留第一个空格为普通空格字符，并将所有后续空格替换为不间断空格实体 NBSP。

---