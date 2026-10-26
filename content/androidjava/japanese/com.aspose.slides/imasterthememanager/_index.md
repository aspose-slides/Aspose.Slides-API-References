---
title: IMasterThemeManager
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションのマスターテーマへのアクセスを提供します。
type: docs
url: /ja/com.aspose.slides/imasterthememanager/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IMasterThemeManager extends IThemeManager
```

プレゼンテーションのマスターテーマへのアクセスを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme が継承された有効なテーマ (Presentation.MasterTheme) を上書きするかどうかを判断します。 |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | OverrideTheme が継承された有効なテーマ (Presentation.MasterTheme) を上書きするかどうかを判断します。 |
| [getOverrideTheme()](#getOverrideTheme--) | 上書きされるテーマオブジェクトを返します。 |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | 上書きされるテーマオブジェクトを返します。 |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

OverrideTheme が継承された有効なテーマ (Presentation.MasterTheme) を上書きするかどうかを判断します。 読み取り/書き込み boolean。

**戻り値:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public abstract void setOverrideThemeEnabled(boolean value)
```

OverrideTheme が継承された有効なテーマ (Presentation.MasterTheme) を上書きするかどうかを判断します。 読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IMasterTheme getOverrideTheme()
```

上書きされるテーマオブジェクトを返します。 読み取り/書き込み [IMasterTheme](../../com.aspose.slides/imastertheme)。

**戻り値:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public abstract void setOverrideTheme(IMasterTheme value)
```

上書きされるテーマオブジェクトを返します。 読み取り/書き込み [IMasterTheme](../../com.aspose.slides/imastertheme)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |