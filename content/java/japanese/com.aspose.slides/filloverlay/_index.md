---
title: FillOverlay
second_title: Aspose.Slides for Java API リファレンス
description: Fill Overlay 効果を表します。
type: docs
url: /ja/com.aspose.slides/filloverlay/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Fill Overlay 効果を表します。Fill Overlay はオブジェクトの追加の塗りつぶしを指定し、2 つの塗りつぶしをブレンドするために使用できます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Gets effective Fill Overlay effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [FillOverlay](../../com.aspose.slides/filloverlay) is equal to the current [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Fill format. 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. 読み取り/書き込み [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**戻り値:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. 読み取り/書き込み [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Gets effective Fill Overlay effect data with the inheritance applied.

**戻り値:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. 読み取り専用 long.

**戻り値:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [FillOverlay](../../com.aspose.slides/filloverlay) is equal to the current [FillOverlay](../../com.aspose.slides/filloverlay).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | The [FillOverlay](../../com.aspose.slides/filloverlay) to compare. |

**戻り値:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**戻り値:**
int - A hash code for the current object.