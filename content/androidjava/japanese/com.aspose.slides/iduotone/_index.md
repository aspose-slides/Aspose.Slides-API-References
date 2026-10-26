---
title: IDuotone
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: Duotone エフェクトを表します。
type: docs
url: /ja/com.aspose.slides/iduotone/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IDuotone extends IImageTransformOperation, IAccessiblePVIObject<IDuotoneEffectiveData>
```

Duotone エフェクトを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColor1()](#getColor1--) | 暗いピクセルの対象カラー形式を返します。 |
| [getColor2()](#getColor2--) | 明るいピクセルの対象カラー形式を返します。 |
### getColor1() {#getColor1--}
```
public abstract IColorFormat getColor1()
```


暗いピクセルの対象カラー形式を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public abstract IColorFormat getColor2()
```


明るいピクセルの対象カラー形式を返します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)