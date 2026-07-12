---
title: BaseOverrideThemeManager
second_title: Aspose.Slides for Android の Java API リファレンス
description: オーバーライドされたさまざまなテーマにアクセスできるクラスの基底クラスです。
type: docs
url: /ja/com.aspose.slides/baseoverridethememanager/
---
**継承:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**実装されている全インターフェイス:**  
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)  
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

オーバーライドされたさまざまなテーマタイプにアクセスできるクラスの基底クラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | オーバーライドテーマオブジェクトを返します。 |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | オーバーライドテーマオブジェクトを返します。 |
| [createThemeEffective()](#createThemeEffective--) | テーマオブジェクトを返します。 |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme が継承された有効なテーマをオーバーライドするかどうかを判定します。 |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | スライドに追加のカラースキームを適用します。 |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

オーバーライドテーマオブジェクトを返します。 読み書き [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**戻り値:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)

### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

オーバーライドテーマオブジェクトを返します。 読み書き [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

テーマオブジェクトを返します。

**戻り値:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

OverrideTheme が継承された有効なテーマをオーバーライドするかどうかを判定します。 OverrideTheme を有効にするには OverrideTheme.Init*() メソッドを使用し、無効にするには OverrideTheme.Clear() メソッドを使用します。 読み取り専用 boolean。

**戻り値:**  
boolean

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

スライドに追加のカラースキームを適用します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) オブジェクト。 |