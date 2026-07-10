---
title: CompressionLevel
second_title: Aspose.Slides for Android via Java API 参考文档
description: 为 OpenXML 文件指定 ZIP 压缩级别。
type: docs
url: /zh/com.aspose.slides/compressionlevel/
---
**继承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionLevel extends System.Enum
```

为 OpenXML 文件指定 ZIP 压缩级别。更高的级别可提供更好的压缩率，但会导致处理速度变慢。

## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 不进行压缩。 |
| [Level1](#Level1) | 最快的压缩速度，压缩率最低。 |
| [Level2](#Level2) | 比 [Level1](../../com.aspose.slides/compressionlevel\#Level1) 稍好一点的压缩率，且压缩速度更快。 |
| [Level3](#Level3) | 在中等性能影响下，提供比 [Level2](../../com.aspose.slides/compressionlevel\#Level2) 更好的压缩。 |
| [Level4](#Level4) | 提供比 [Level3](../../com.aspose.slides/compressionlevel\#Level3) 更好的压缩。 |
| [Level5](#Level5) | 在额外的处理时间下，提供比 [Level4](../../com.aspose.slides/compressionlevel\#Level4) 更高的压缩率。 |
| [Level6](#Level6) | 标准压缩，在压缩速度和文件大小之间取得良好平衡。 |
| [Level7](#Level7) | 在处理速度较慢的情况下，提供比 [Level6](../../com.aspose.slides/compressionlevel\#Level6) 更高的压缩率。 |
| [Level8](#Level8) | 提供比 [Level7](../../com.aspose.slides/compressionlevel\#Level7) 更高的压缩率。 |
| [Level9](#Level9) | 最大压缩率。 |

### None {#None}
```
public static final int None
```

不进行压缩。文件保持原样存储。

### Level1 {#Level1}
```
public static final int Level1
```

最快的压缩速度，压缩率最低。

### Level2 {#Level2}
```
public static final int Level2
```

比 [Level1](../../com.aspose.slides/compressionlevel\#Level1) 稍好一点的压缩率，且压缩速度更快。

### Level3 {#Level3}
```
public static final int Level3
```

在中等性能影响下，提供比 [Level2](../../com.aspose.slides/compressionlevel\#Level2) 更好的压缩。

### Level4 {#Level4}
```
public static final int Level4
```

提供比 [Level3](../../com.aspose.slides/compressionlevel\#Level3) 更好的压缩。

### Level5 {#Level5}
```
public static final int Level5
```

在额外的处理时间下，提供比 [Level4](../../com.aspose.slides/compressionlevel\#Level4) 更高的压缩率。

### Level6 {#Level6}
```
public static final int Level6
```

标准压缩，在压缩速度和文件大小之间取得良好平衡。默认压缩级别。

### Level7 {#Level7}
```
public static final int Level7
```

在处理速度较慢的情况下，提供比 [Level6](../../com.aspose.slides/compressionlevel\#Level6) 更高的压缩率。

### Level8 {#Level8}
```
public static final int Level8
```

提供比 [Level7](../../com.aspose.slides/compressionlevel\#Level7) 更高的压缩率。

### Level9 {#Level9}
```
public static final int Level9
```

最大压缩率。产生最小的文件大小，但处理速度最慢。