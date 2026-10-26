---
title: LinkEmbedDecision
second_title: 适用于 Android 的 Aspose.Slides via Java API 参考
description: 确定对象在保存期间的处理方式。
type: docs
url: /zh/com.aspose.slides/linkembeddecision/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LinkEmbedDecision extends System.Enum
```

Determines how object will be processed during saving.
## 字段

| 字段 | 描述 |
| --- | --- |
| [Link](#Link) | Object 将以外部方式存储，通过 URL 引用 |
| [Embed](#Embed) | Object 应嵌入生成的文件中（如果可能）。 |
| [Ignore](#Ignore) | Object 将被忽略。 |
### 链接 {#Link}
```
public static final int Link
```


Object 将以外部方式存储，通过 URL 引用

### 嵌入 {#Embed}
```
public static final int Embed
```


Object 应嵌入生成的文件中（如果可能）。如果嵌入不可行，GetUrl 将被调用，并根据结果，将 Object 通过 URL 引用或忽略。

### 忽略 {#Ignore}
```
public static final int Ignore
```


Object 将被忽略。