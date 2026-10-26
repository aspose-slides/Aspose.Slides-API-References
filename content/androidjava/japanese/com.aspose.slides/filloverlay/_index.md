---
title: FillOverlay
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: Fill Overlay エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/filloverlay/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect  
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Fill Overlay エフェクトを表します。Fill Overlay は、オブジェクトに追加の塗りつぶしを指定し、2 つの塗りつぶしをブレンドするために使用できます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 塗りつぶし形式。 |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | 継承が適用された実効的な Fill Overlay エフェクト データを取得します。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [FillOverlay](../../com.aspose.slides/filloverlay) が現在の [FillOverlay](../../com.aspose.slides/filloverlay) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型に対するハッシュ関数として機能します。 |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

塗りつぶし形式。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値：**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode。読み取り/書き込み [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**戻り値：**  
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode。読み取り/書き込み [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**パラメーター：**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

継承が適用された実効的な Fill Overlay エフェクト データを取得します。

**戻り値：**  
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version。読み取り専用 long。

**戻り値：**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

指定された [FillOverlay](../../com.aspose.slides/filloverlay) が現在の [FillOverlay](../../com.aspose.slides/filloverlay) と等しいかどうかを判断します。

**パラメーター：**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [FillOverlay](../../com.aspose.slides/filloverlay)。 |

**戻り値：**  
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

特定の型に対するハッシュ関数として機能します。

**戻り値：**  
int - 現在のオブジェクトのハッシュコード。