---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for Android via Java API 参考
description: 指定在 Markdown 导出期间应如何处理重复的普通空格字符。
type: docs
url: /zh/com.aspose.slides/handlerepeatedspaces/
---
**继承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

指定在 Markdown 导出期间如何处理重复的普通空格字符。

## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 所有空格均以普通空格字符保留，不做任何更改。 |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | 将两个或更多连续普通空格的序列转换为普通空格字符和不换行空格实体（NBSP）交替出现的形式。 |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | 将两个或更多连续普通空格的序列转换为保留第一个普通空格字符，其余空格替换为不换行空格实体（NBSP）。 |

### None {#None}
```
public static final int None
```

所有空格均以普通空格字符保留，不做任何更改。不进行任何转换，多个连续空格将原样导出。

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

将两个或更多连续普通空格的序列转换为普通空格字符和不换行空格实体（NBSP）交替出现的形式。第一个空格始终保留为普通空格。

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

将两个或更多连续普通空格的序列转换为保留第一个普通空格字符，其余空格替换为不换行空格实体（NBSP）。