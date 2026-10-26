---
title: OuterShadow
second_title: Java API リファレンスを使用した Aspose.Slides for Android
description: 外部シャドウ効果を表します。
type: docs
url: /ja/com.aspose.slides/outershadow/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IOuterShadow](../../com.aspose.slides/ioutershadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class OuterShadow implements IOuterShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

外部シャドウ効果を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | ポイント単位のぼかし半径。 |
| [setBlurRadius(double value)](#setBlurRadius-double-) | ポイント単位のぼかし半径。 |
| [getDirection()](#getDirection--) | 度単位のシャドウの方向。 |
| [setDirection(float value)](#setDirection-float-) | 度単位のシャドウの方向。 |
| [getDistance()](#getDistance--) | オブジェクトからのシャドウの距離（ポイント）。 |
| [setDistance(double value)](#setDistance-double-) | オブジェクトからのシャドウの距離（ポイント）。 |
| [getShadowColor()](#getShadowColor--) | シャドウの色。 |
| [getRectangleAlign()](#getRectangleAlign--) | 矩形の配置。 |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | 矩形の配置。 |
| [getSkewHorizontal()](#getSkewHorizontal--) | 度単位の水平方向のスキュー角度。 |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | 度単位の水平方向のスキュー角度。 |
| [getSkewVertical()](#getSkewVertical--) | 度単位の垂直方向のスキュー角度。 |
| [setSkewVertical(double value)](#setSkewVertical-double-) | 度単位の垂直方向のスキュー角度。 |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | シャドウがシェイプと共に回転するかどうかを示します。 |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | シャドウがシェイプと共に回転するかどうかを示します。 |
| [getScaleHorizontal()](#getScaleHorizontal--) | 元のサイズのパーセンテージで表す水平方向の拡大率。 |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | 元のサイズのパーセンテージで表す水平方向の拡大率。 |
| [getScaleVertical()](#getScaleVertical--) | 元のサイズのパーセンテージで表す垂直方向の拡大率。 |
| [setScaleVertical(double value)](#setScaleVertical-double-) | 元のサイズのパーセンテージで表す垂直方向の拡大率。 |
| [getEffective()](#getEffective--) | 継承が適用された効果的な外部シャドウ効果データを取得します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された [OuterShadow](../../com.aspose.slides/outershadow) が現在の [OuterShadow](../../com.aspose.slides/outershadow) と等しいかどうかを判断します。 |
| [hashCode()](#hashCode--) | 特定の型のハッシュ関数として機能します。 |
### getBlurRadius() {#getBlurRadius--}
```
public final double getBlurRadius()
```


ポイント単位のぼかし半径。デフォルト値 - 0 pt。読み書き可能 double。

**戻り値:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public final void setBlurRadius(double value)
```


ポイント単位のぼかし半径。デフォルト値 - 0 pt。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getDirection() {#getDirection--}
```
public final float getDirection()
```


度単位のシャドウの方向（左から右へ）。デフォルト値 - 0 °（左から右へ）。読み書き可能 float。

**戻り値:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```


度単位のシャドウの方向（左から右へ）。デフォルト値 - 0 °（左から右へ）。読み書き可能 float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```


オブジェクトからのシャドウの距離（ポイント）。デフォルト値 - 0 pt。読み書き可能 double。

**戻り値:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


オブジェクトからのシャドウの距離（ポイント）。デフォルト値 - 0 pt。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```


シャドウの色。デフォルト値 - 自動的な黒（テーマ依存）。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat)。

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public final byte getRectangleAlign()
```


矩形の配置。デフォルト値 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。読み書き可能 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**戻り値:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public final void setRectangleAlign(byte value)
```


矩形の配置。デフォルト値 - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom)。読み書き可能 [RectangleAlignment](../../com.aspose.slides/rectanglealignment)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getSkewHorizontal() {#getSkewHorizontal--}
```
public final double getSkewHorizontal()
```


度単位の水平方向のスキュー角度。デフォルト値 - 0 °。読み書き可能 double。

**戻り値:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public final void setSkewHorizontal(double value)
```


度単位の水平方向のスキュー角度。デフォルト値 - 0 °。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getSkewVertical() {#getSkewVertical--}
```
public final double getSkewVertical()
```


度単位の垂直方向のスキュー角度。デフォルト値 - 0 °。読み書き可能 double。

**戻り値:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public final void setSkewVertical(double value)
```


度単位の垂直方向のスキュー角度。デフォルト値 - 0 °。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public final boolean getRotateShadowWithShape()
```


シャドウがシェイプと共に回転するかどうかを示します。デフォルト値 - true。読み書き可能 boolean。

**戻り値:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public final void setRotateShadowWithShape(boolean value)
```


シャドウがシェイプと共に回転するかどうかを示します。デフォルト値 - true。読み書き可能 boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getScaleHorizontal() {#getScaleHorizontal--}
```
public final double getScaleHorizontal()
```


元のサイズのパーセンテージで表す水平方向の拡大率。負のスケーリングは反転を引き起こします。デフォルト値 - 100%。読み書き可能 double。

**戻り値:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public final void setScaleHorizontal(double value)
```


元のサイズのパーセンテージで表す水平方向の拡大率。負のスケーリングは反転を引き起こします。デフォルト値 - 100%。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getScaleVertical() {#getScaleVertical--}
```
public final double getScaleVertical()
```


元のサイズのパーセンテージで表す垂直方向の拡大率。負のスケーリングは反転を引き起こします。デフォルト値 - 100%。読み書き可能 double。

**戻り値:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public final void setScaleVertical(double value)
```


元のサイズのパーセンテージで表す垂直方向の拡大率。負のスケーリングは反転を引き起こします。デフォルト値 - 100%。読み書き可能 double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final IOuterShadowEffectiveData getEffective()
```


継承が適用された効果的な外部シャドウ効果データを取得します。

**戻り値:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata) - A [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)。
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


バージョン。読み取り専用 long。

**戻り値:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


親 IPresentationComponent を返します。読み取り専用 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**戻り値:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された [OuterShadow](../../com.aspose.slides/outershadow) が現在の [OuterShadow](../../com.aspose.slides/outershadow) と等しいかどうかを判断します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | 比較対象の [OuterShadow](../../com.aspose.slides/outershadow)。 |

**戻り値:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


特定の型のハッシュ関数として機能します。

**戻り値:**
int - 現在のオブジェクトのハッシュコード。