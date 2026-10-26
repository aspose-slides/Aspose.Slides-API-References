---
title: IOverrideThemeManager
second_title: Aspose.Slides for Java API リファレンス
description: さまざまなタイプのオーバーライドされたテーマへのアクセスを提供します。
type: docs
url: /ja/com.aspose.slides/ioverridethememanager/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

異なるタイプのオーバーライドされたテーマへのアクセスを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme が継承された有効なテーマをオーバーライドするかどうかを判断します。 |
| [getOverrideTheme()](#getOverrideTheme--) | オーバーライドされたテーマオブジェクトを返します。 |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | オーバーライドされたテーマオブジェクトを返します。 |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

OverrideTheme が継承された有効なテーマをオーバーライドするかどうかを判断します。 OverrideTheme のオーバーライドを有効にするには OverrideTheme.Init*() メソッドを使用します。 OverrideTheme のオーバーライドを無効にするには OverrideTheme.Clear() メソッドを使用します。 読み取り専用 boolean.

**戻り値:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

オーバーライドされたテーマオブジェクトを返します。 読み書き [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**戻り値:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

オーバーライドされたテーマオブジェクトを返します。 読み書き [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |