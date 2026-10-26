---
title: IFillOverlay
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Fill Overlay エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/ifilloverlay/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Fill Overlay エフェクトを表します。Fill overlay は、オブジェクトに追加の塗りを指定し、2つの塗りをブレンドするために使用できます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. 読み書き [FillBlendMode](../../com.aspose.slides/fillblendmode).

**戻り値:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. 読み書き [FillBlendMode](../../com.aspose.slides/fillblendmode).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Fill format. 読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat).

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)