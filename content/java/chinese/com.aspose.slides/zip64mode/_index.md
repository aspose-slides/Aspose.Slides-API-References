---
title: Zip64Mode
second_title: Aspose.Slides for Java API 参考
description: 指定何时为 OpenXML 文件使用 ZIP64 格式扩展。
type: docs
url: /zh/com.aspose.slides/zip64mode/
---
**继承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

指定何时为 OpenXML 文件使用 ZIP64 格式扩展。

--------------------

OpenXML 文件是一个 ZIP 存档，对文件的未压缩大小、压缩大小以及存档的总体大小都有 4 GB（2^32 字节）的限制，并且存档中最多只能包含 65,535（2^16-1）个文件。ZIP64 格式扩展将这些限制提升至 2^64。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Never](#Never) | 不要使用 ZIP64 格式扩展。 |
| [IfNecessary](#IfNecessary) | 如有必要，使用 ZIP64 格式扩展。 |
| [Always](#Always) | 始终使用 ZIP64 格式扩展。 |
### Never {#Never}
```
public static final int Never
```

不要使用 ZIP64 格式扩展。

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```

如有必要，使用 ZIP64 格式扩展。

### Always {#Always}
```
public static final int Always
```

始终使用 ZIP64 格式扩展。