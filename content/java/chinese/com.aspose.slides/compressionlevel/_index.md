---
title: CompressionLevel
second_title: Aspose.Slides for Java API 参考
description: 指定 OpenXML 文件的 ZIP 压缩级别。
type: docs
url: /zh/com.aspose.slides/compressionlevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionLevel extends System.Enum
```

指定 OpenXML 文件的 ZIP 压缩级别。更高的级别可提供更好的压缩率，但处理速度更慢。

## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 未应用压缩。 |
| [Level1](#Level1) | 最快的压缩，压缩率最低。 |
| [Level2](#Level2) | 压缩速度更快，压缩率略好于 [Level1](../../com.aspose.slides/compressionlevel\#Level1)。 |
| [Level3](#Level3) | 在适度的性能影响下，压缩效果优于 [Level2](../../com.aspose.slides/compressionlevel\#Level2)。 |
| [Level4](#Level4) | 压缩效果优于 [Level3](../../com.aspose.slides/compressionlevel\#Level3)。 |
| [Level5](#Level5) | 在增加处理时间的情况下，压缩效果优于 [Level4](../../com.aspose.slides/compressionlevel\#Level4)。 |
| [Level6](#Level6) | 标准压缩，在压缩速度和文件大小之间取得良好平衡。 |
| [Level7](#Level7) | 在处理速度较慢的情况下，压缩率高于 [Level6](../../com.aspose.slides/compressionlevel\#Level6)。 |
| [Level8](#Level8) | 压缩率高于 [Level7](../../com.aspose.slides/compressionlevel\#Level7)。 |
| [Level9](#Level9) | 最大压缩。 |
### None {#None}
```
public static final int None
```

未应用压缩。文件保持原样存储。

### Level1 {#Level1}
```
public static final int Level1
```

最快的压缩，压缩率最低。

### Level2 {#Level2}
```
public static final int Level2
```

压缩速度更快，压缩率略好于 [Level1](../../com.aspose.slides/compressionlevel\#Level1)。

### Level3 {#Level3}
```
public static final int Level3
```

在适度的性能影响下，压缩效果优于 [Level2](../../com.aspose.slides/compressionlevel\#Level2)。

### Level4 {#Level4}
```
public static final int Level4
```

压缩效果优于 [Level3](../../com.aspose.slides/compressionlevel\#Level3)。

### Level5 {#Level5}
```
public static final int Level5
```

在增加处理时间的情况下，压缩效果优于 [Level4](../../com.aspose.slides/compressionlevel\#Level4)。

### Level6 {#Level6}
```
public static final int Level6
```

标准压缩，在压缩速度和文件大小之间取得良好平衡。默认的压缩级别。

### Level7 {#Level7}
```
public static final int Level7
```

在处理速度较慢的情况下，压缩率高于 [Level6](../../com.aspose.slides/compressionlevel\#Level6)。

### Level8 {#Level8}
```
public static final int Level8
```

压缩率高于 [Level7](../../com.aspose.slides/compressionlevel\#Level7)。

### Level9 {#Level9}
```
public static final int Level9
```

最大压缩。生成最小的文件大小，但处理速度最慢。