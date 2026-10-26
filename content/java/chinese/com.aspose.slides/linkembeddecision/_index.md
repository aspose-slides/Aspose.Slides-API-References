---
title: LinkEmbedDecision
second_title: Aspose.Slides 用于 Java 的 API 参考
description: 确定对象在保存期间的处理方式。
type: docs
url: /zh/com.aspose.slides/linkembeddecision/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

确定对象在保存期间的处理方式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Link](#Link) | 对象将被外部存储，通过 URL 引用 |
| [Embed](#Embed) | 如果可能，应该将对象嵌入生成的文件中。 |
| [Ignore](#Ignore) | 对象将被忽略。 |
### 链接 {#Link}
```
public static final int Link
```


对象将被外部存储，通过 URL 引用

### 嵌入 {#Embed}
```
public static final int Embed
```


如果可能，应该将对象嵌入生成的文件中。如果嵌入不可能，将调用 GetUrl，并根据结果，对象将通过 URL 引用或被忽略。

### 忽略 {#Ignore}
```
public static final int Ignore
```


对象将被忽略。