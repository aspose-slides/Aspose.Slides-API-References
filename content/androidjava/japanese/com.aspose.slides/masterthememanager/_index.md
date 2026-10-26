---
title: MasterThemeManager
second_title: Java API を介した Android 用 Aspose.Slides のリファレンス
description: プレゼンテーションのマスターテーマへのアクセスを提供します。
type: docs
url: /ja/com.aspose.slides/masterthememanager/
---
**継承:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)  
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

プレゼンテーション マスター テーマへのアクセスを提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | 上書きテーマオブジェクトを返します。 |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | 上書きテーマオブジェクトを返します。 |
| [createThemeEffective()](#createThemeEffective--) | テーマオブジェクトを返します。 |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | OverrideTheme が継承された有効なテーマ (Presentation.MasterTheme) を上書きするかどうかを判断します。 |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | OverrideTheme が継承された有効なテーマ (Presentation.MasterTheme) を上書きするかどうかを判断します。 |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | スライドに余分なカラースキームを適用します。 |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

上書きテーマオブジェクトを返します。読み取り/書き込み [IMasterTheme](../../com.aspose.slides/imastertheme)。

**戻り値:**  
[IMasterTheme](../../com.aspose.slides/imastertheme)

### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

上書きテーマオブジェクトを返します。読み取り/書き込み [IMasterTheme](../../com.aspose.slides/imastertheme)。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

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

OverrideTheme が継承された有効なテーマ (Presentation.MasterTheme) を上書きするかどうかを判断します。読み取り/書き込み boolean。

**戻り値:**  
boolean

### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

OverrideTheme が継承された有効なテーマ (Presentation.MasterTheme) を上書きするかどうかを判断します。読み取り/書き込み boolean。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

スライドに余分なカラースキームを適用します。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) オブジェクト。 |