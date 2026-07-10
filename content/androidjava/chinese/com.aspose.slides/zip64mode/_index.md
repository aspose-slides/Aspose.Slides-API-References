---
title: Zip64Mode
second_title: Aspose.Slides for Android via Java API 参考
description: 指定何时在 OpenXML 文件中使用 ZIP64 格式扩展。
type: docs
url: /zh/com.aspose.slides/zip64mode/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

指定何时在 OpenXML 文件中使用 ZIP64 格式扩展。

--------------------

OpenXML 文件是一个 ZIP 存档，对未压缩文件大小、压缩后文件大小以及整个存档的总大小都有限制为 4 GB（2^32 字节），并且存档中的文件数量限制为 65 535（2^16-1）。ZIP64 格式扩展将这些限制提升至 2^64。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Never](#Never) | 不使用 ZIP64 格式扩展。 |
| [IfNecessary](#IfNecessary) | 如有必要，使用 ZIP64 格式扩展。 |
| [Always](#Always) | 始终使用 ZIP64 格式扩展。 |
### Never {#Never}
```
public static final int Never
```

不使用 ZIP64 格式扩展。

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