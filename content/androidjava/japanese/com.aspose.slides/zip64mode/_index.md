---
title: Zip64Mode
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: OpenXML ファイルで ZIP64 形式拡張子を使用するタイミングを指定します。
type: docs
url: /ja/com.aspose.slides/zip64mode/
---
**継承:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class Zip64Mode extends System.Enum
```

OpenXML ファイルで ZIP64 形式拡張子を使用するタイミングを指定します。

--------------------

OpenXML ファイルは ZIP アーカイブで、ファイルの非圧縮サイズ、圧縮サイズ、アーカイブ全体のサイズに 4 GB (2^32 バイト) の制限があり、アーカイブ内のファイル数は 65 535 (2^16-1) 個に制限されています。ZIP64 形式拡張子はこれらの制限を 2^64 に拡大します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Never](#Never) | ZIP64 形式拡張子を使用しないでください。 |
| [IfNecessary](#IfNecessary) | 必要に応じて ZIP64 形式拡張子を使用します。 |
| [Always](#Always) | 常に ZIP64 形式拡張子を使用します。 |
### Never {#Never}
```
public static final int Never
```


ZIP64 形式拡張子を使用しないでください。

### IfNecessary {#IfNecessary}
```
public static final int IfNecessary
```


必要に応じて ZIP64 形式拡張子を使用します。

### Always {#Always}
```
public static final int Always
```


常に ZIP64 形式拡張子を使用します。