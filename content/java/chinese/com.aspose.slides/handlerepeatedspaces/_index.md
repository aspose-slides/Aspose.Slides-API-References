---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for Java API 参考
description: 指定在 Markdown 导出期间应如何处理重复的常规空格字符。
type: docs
url: /zh/com.aspose.slides/handlerepeatedspaces/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

指定在 Markdown 导出期间应如何处理重复的常规空格字符。
## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 所有空格都保留为常规空格字符，未作任何更改。 |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | 通过在常规空格字符和不间断空格实体 NBSP 之间交替，将两个或更多连续的常规空格序列进行转换。 |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | 通过保留第一个空格为常规空格字符，并将所有后续空格替换为不间断空格实体 NBSP，将两个或更多连续的常规空格序列进行转换。 |
### None {#None}
```
public static final int None
```

所有空格都保留为常规空格字符，未作任何更改。未应用任何转换，多个连续空格将按原样导出。

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

通过在常规空格字符和不间断空格实体 NBSP 之间交替，将两个或更多连续的常规空格序列进行转换。第一个空格始终保留为常规空格。

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

通过保留第一个空格为常规空格字符，并将所有后续空格替换为不间断空格实体 NBSP，将两个或更多连续的常规空格序列进行转换。