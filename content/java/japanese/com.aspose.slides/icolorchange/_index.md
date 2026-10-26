---
title: IColorChange
second_title: Aspose.Slides の Java API リファレンス
description: 色の変更効果を表します。
type: docs
url: /ja/com.aspose.slides/icolorchange/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

色の変更効果を表します。FromColor のインスタンスは ToColor のインスタンスに置き換えられます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 置き換えられる色。 |
| [getToColor()](#getToColor--) | 置き換える色。 |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```

置き換えられる色。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```

置き換える色。 読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)