---
title: Format
second_title: Java APIリファレンスによるAndroid用Aspose.Slides
description: チャートの書式プロパティを表します。
type: docs
url: /ja/com.aspose.slides/format/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IFormat](../../com.aspose.slides/iformat)  
```
public final class Format extends PVIObject implements IFormat
```

チャートの書式プロパティを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFill()](#getFill--) | チャートの塗りつぶしスタイルプロパティを返します。 |
| [getLine()](#getLine--) | チャートの線スタイルプロパティを返します。 |
| [getEffect()](#getEffect--) | チャートで使用されるエフェクトを返します。 |
| [getEffect3D()](#getEffect3D--) | チャートの 3D 書式を返します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long.

**戻り値:**  
long

### getFill() {#getFill--}
```
public final IFillFormat getFill()
```

チャートの塗りつぶしスタイルプロパティを返します。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat).

**戻り値:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getLine() {#getLine--}
```
public final ILineFormat getLine()
```

チャートの線スタイルプロパティを返します。読み取り専用 [ILineFormat](../../com.aspose.slides/ilineformat).

**戻り値:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getEffect() {#getEffect--}
```
public final IEffectFormat getEffect()
```

チャートで使用されるエフェクトを返します。読み取り専用 [IEffectFormat](../../com.aspose.slides/ieffectformat).

**戻り値:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getEffect3D() {#getEffect3D--}
```
public final IThreeDFormat getEffect3D()
```

チャートの 3D 書式を返します。読み取り専用 [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**戻り値:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)