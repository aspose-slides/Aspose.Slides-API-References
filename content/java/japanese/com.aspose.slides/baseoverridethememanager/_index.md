---
title: BaseOverrideThemeManager
second_title: Aspose.Slides の Java API リファレンス
description: オーバーライドされたテーマのさまざまなタイプにアクセスできるクラスの基底クラスです。
type: docs
url: /ja/com.aspose.slides/baseoverridethememanager/
---
**継承:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

オーバーライドされたテーマのさまざまなタイプにアクセスできるクラスの基底クラスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | オーバーライドされたテーマオブジェクトを返します。 |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | オーバーライドされたテーマオブジェクトを返します。 |
| [createThemeEffective()](#createThemeEffective--) | テーマオブジェクトを返します。 |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme が継承された有効なテーマをオーバーライドするかどうかを判定します。 |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | スライドに追加のカラースキームを適用します。 |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

オーバーライドされたテーマオブジェクトを返します。読み取り/書き込み [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**戻り値:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

オーバーライドされたテーマオブジェクトを返します。読み取り/書き込み [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**パラメーター:**
| パラメーター | 型 | 説明 |
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

OverrideTheme が継承された有効なテーマをオーバーライドするかどうかを判定します。オーバーライドを有効にするには OverrideTheme.Init\*() メソッドを使用します。オーバーライドを無効にするには OverrideTheme.Clear() メソッドを使用します。読み取り専用 boolean。

**戻り値:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

スライドに追加のカラースキームを適用します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) オブジェクト。 |