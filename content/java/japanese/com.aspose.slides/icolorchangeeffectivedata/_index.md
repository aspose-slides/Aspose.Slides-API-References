---
title: IColorChangeEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: Color Change 効果を表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/icolorchangeeffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Color Change 効果を表す不変オブジェクトです。FromColor のインスタンスは ToColor のインスタンスに置き換えられます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 置き換えられる色。 |
| [getToColor()](#getToColor--) | 置き換える色。 |
| [getUseAlpha()](#getUseAlpha--) | アルファ成分を使用するかどうかを決定するブール値を返します。 |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```

置き換えられる色。読み取り専用 java.awt.Color.

**戻り値:**
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```

置き換える色。読み取り専用 java.awt.Color.

**戻り値:**
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```

アルファ成分を使用するかどうかを決定するブール値を返します。読み取り専用 boolean.

**戻り値:**
boolean