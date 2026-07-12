---
title: CompressionLevel
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: OpenXML ファイルの ZIP 圧縮レベルを指定します。
type: docs
url: /ja/com.aspose.slides/compressionlevel/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionLevel extends System.Enum
```

OpenXML ファイルの ZIP 圧縮レベルを指定します。レベルが高いほど圧縮率は向上しますが、処理速度は遅くなります。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [None](#None) | 圧縮は適用されません。 |
| [Level1](#Level1) | 最も高速な圧縮で、圧縮率は最低です。 |
| [Level2](#Level2) | [Level1](../../com.aspose.slides/compressionlevel\#Level1) よりわずかに高い圧縮率で、より高速な圧縮を行います。 |
| [Level3](#Level3) | [Level2](../../com.aspose.slides/compressionlevel\#Level2) より良い圧縮を提供しますが、パフォーマンスへの影響は中程度です。 |
| [Level4](#Level4) | [Level3](../../com.aspose.slides/compressionlevel\#Level3) より良い圧縮を提供します。 |
| [Level5](#Level5) | [Level4](../../com.aspose.slides/compressionlevel\#Level4) より改善された圧縮を提供しますが、処理時間が追加されます。 |
| [Level6](#Level6) | 標準的な圧縮で、圧縮速度とファイルサイズのバランスが取れています。 |
| [Level7](#Level7) | [Level6](../../com.aspose.slides/compressionlevel\#Level6) より高い圧縮を提供しますが、処理は遅くなります。 |
| [Level8](#Level8) | [Level7](../../com.aspose.slides/compressionlevel\#Level7) より高い圧縮を提供します。 |
| [Level9](#Level9) | 最大圧縮。 |

### なし {#None}
```
public static final int None
```

圧縮は適用されません。ファイルはそのまま保存されます。

### レベル1 {#Level1}
```
public static final int Level1
```

最も高速な圧縮で、圧縮率は最低です。

### レベル2 {#Level2}
```
public static final int Level2
```

[Level1](../../com.aspose.slides/compressionlevel\#Level1) よりわずかに高い圧縮率で、より高速な圧縮を行います。

### レベル3 {#Level3}
```
public static final int Level3
```

[Level2](../../com.aspose.slides/compressionlevel\#Level2) より良い圧縮を提供しますが、パフォーマンスへの影響は中程度です。

### レベル4 {#Level4}
```
public static final int Level4
```

[Level3](../../com.aspose.slides/compressionlevel\#Level3) より良い圧縮を提供します。

### レベル5 {#Level5}
```
public static final int Level5
```

[Level4](../../com.aspose.slides/compressionlevel\#Level4) より改善された圧縮を提供しますが、処理時間が追加されます。

### レベル6 {#Level6}
```
public static final int Level6
```

標準的な圧縮で、圧縮速度とファイルサイズのバランスが取れています。デフォルトの圧縮レベルです。

### レベル7 {#Level7}
```
public static final int Level7
```

[Level6](../../com.aspose.slides/compressionlevel\#Level6) より高い圧縮を提供しますが、処理は遅くなります。

### レベル8 {#Level8}
```
public static final int Level8
```

[Level7](../../com.aspose.slides/compressionlevel\#Level7) より高い圧縮を提供します。

### レベル9 {#Level9}
```
public static final int Level9
```

最大圧縮です。最も小さなファイルサイズを生成し、処理速度は最も遅くなります。