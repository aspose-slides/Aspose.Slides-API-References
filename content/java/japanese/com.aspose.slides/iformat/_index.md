---
title: IFormat
second_title: Aspose.Slides for Java API Reference
description: Represents chart format properties.
type: docs
url: /ja/com.aspose.slides/iformat/
---```
public interface IFormat
```

チャートの書式プロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFill()](#getFill--) | Returns fill style properties of a chart. |
| [getLine()](#getLine--) | Returns line style properties of a chart. |
| [getEffect()](#getEffect--) | Returns effects used for a chart. |
| [getEffect3D()](#getEffect3D--) | Returns 3D format of a chart. |
### getFill() {#getFill--}
```
public abstract IFillFormat getFill()
```

チャートの塗りつぶしスタイルプロパティを返します。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getLine() {#getLine--}
```
public abstract ILineFormat getLine()
```

チャートの線スタイルプロパティを返します。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat)。

**戻り値:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffect() {#getEffect--}
```
public abstract IEffectFormat getEffect()
```

チャートで使用されるエフェクトを返します。読み取り専用 [IEffectFormat](../../com.aspose.slides/ieffectformat)。

**戻り値:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getEffect3D() {#getEffect3D--}
```
public abstract IThreeDFormat getEffect3D()
```

チャートの3D書式を返します。読み取り専用 [IThreeDFormat](../../com.aspose.slides/ithreedformat)。

**戻り値:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)