---
title: IColorChangeEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: カラー変更エフェクトを表す不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/icolorchangeeffectivedata/
---
**すべての実装インターフェイス:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

Color Change エフェクトを表す不変オブジェクトです。FromColor のインスタンスは ToColor のインスタンスに置き換えられます。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFromColor()](#getFromColor--) | 置き換えられる色。 |
| [getToColor()](#getToColor--) | 置き換える色。 |
| [getUseAlpha()](#getUseAlpha--) | アルファコンポーネントを使用するかどうかを決定するブール値を返します。 |
### getFromColor() {#getFromColor--}
```
public abstract Integer getFromColor()
```


置き換えられる色。 読み取り専用 java.lang.Integer。

**戻り値:**  
java.lang.Integer
### getToColor() {#getToColor--}
```
public abstract Integer getToColor()
```


置き換える色。 読み取り専用 java.lang.Integer。

**戻り値:**  
java.lang.Integer
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


アルファコンポーネントを使用するかどうかを決定するブール値を返します。 読み取り専用 boolean。

**戻り値:**  
boolean