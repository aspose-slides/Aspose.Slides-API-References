---
title: CompressionLevel
second_title: Aspose.Slides for Android 的 Java API 參考
description: 指定 OpenXML 檔案的 ZIP 壓縮等級。
type: docs
url: /zh-hant/com.aspose.slides/compressionlevel/
---
**繼承:**  
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionLevel extends System.Enum
```

指定 OpenXML 檔案的 ZIP 壓縮等級。較高的等級提供更好的壓縮效果，但處理速度較慢。

## 欄位

| 欄位 | 說明 |
| --- | --- |
| [None](#None) | 不進行壓縮。 |
| [Level1](#Level1) | 最速的壓縮，且壓縮率最低。 |
| [Level2](#Level2) | 較快的壓縮，壓縮率較 [Level1](../../com.aspose.slides/compressionlevel\#Level1) 稍好。 |
| [Level3](#Level3) | 提供比 [Level2](../../com.aspose.slides/compressionlevel\#Level2) 更好的壓縮，且對效能的影響適中。 |
| [Level4](#Level4) | 提供比 [Level3](../../com.aspose.slides/compressionlevel\#Level3) 更好的壓縮。 |
| [Level5](#Level5) | 在 [Level4](../../com.aspose.slides/compressionlevel\#Level4) 基礎上提供改進的壓縮，但需要額外的處理時間。 |
| [Level6](#Level6) | 標準壓縮，在壓縮速度與檔案大小之間取得良好平衡。 |
| [Level7](#Level7) | 提供比 [Level6](../../com.aspose.slides/compressionlevel\#Level6) 更高的壓縮，處理速度較慢。 |
| [Level8](#Level8) | 提供比 [Level7](../../com.aspose.slides/compressionlevel\#Level7) 更高的壓縮。 |
| [Level9](#Level9) | 最大壓縮。 |

### None {#None}
```
public static final int None
```

不進行壓縮。檔案會原樣儲存。

### Level1 {#Level1}
```
public static final int Level1
```

最速的壓縮，且壓縮率最低。

### Level2 {#Level2}
```
public static final int Level2
```

較快的壓縮，壓縮率較 [Level1](../../com.aspose.slides/compressionlevel\#Level1) 稍好。

### Level3 {#Level3}
```
public static final int Level3
```

提供比 [Level2](../../com.aspose.slides/compressionlevel\#Level2) 更好的壓縮，且對效能的影響適中。

### Level4 {#Level4}
```
public static final int Level4
```

提供比 [Level3](../../com.aspose.slides/compressionlevel\#Level3) 更好的壓縮。

### Level5 {#Level5}
```
public static final int Level5
```

在 [Level4](../../com.aspose.slides/compressionlevel\#Level4) 基礎上提供改進的壓縮，但需要額外的處理時間。

### Level6 {#Level6}
```
public static final int Level6
```

標準壓縮，在壓縮速度與檔案大小之間取得良好平衡。預設的壓縮等級。

### Level7 {#Level7}
```
public static final int Level7
```

提供比 [Level6](../../com.aspose.slides/compressionlevel\#Level6) 更高的壓縮，處理速度較慢。

### Level8 {#Level8}
```
public static final int Level8
```

提供比 [Level7](../../com.aspose.slides/compressionlevel\#Level7) 更高的壓縮。

### Level9 {#Level9}
```
public static final int Level9
```

最大壓縮。產生最小的檔案大小，但處理速度最慢。