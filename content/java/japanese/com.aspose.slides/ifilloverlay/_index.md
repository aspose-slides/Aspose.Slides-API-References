---
title: IFillOverlay
second_title: Aspose.Slides for Java API リファレンス
description: Fill Overlay 効果を表します。
type: docs
url: /ja/com.aspose.slides/ifilloverlay/
---
**すべての実装インターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

オブジェクトに追加の塗りを指定し、2 つの塗りをブレンドするために使用できる Fill Overlay 効果を表します。

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