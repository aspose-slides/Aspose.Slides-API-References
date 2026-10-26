---
title: BaseOverrideThemeManager
second_title: Aspose.Slides for Java API 參考文件
description: 用於提供存取不同類型已覆寫佈景主題之類別的基底類別。
type: docs
url: /zh-hant/com.aspose.slides/baseoverridethememanager/
---
**繼承：**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**所有已實作的介面：**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

用於提供對不同類型已覆寫佈景主題存取的類別之基底類別。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | 傳回覆寫佈景主題物件。 |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | 傳回覆寫佈景主題物件。 |
| [createThemeEffective()](#createThemeEffective--) | 傳回佈景主題物件。 |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 判斷 OverrideTheme 是否覆寫繼承的有效佈景主題。 |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | 將額外的配色方案套用至投影片。 |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


傳回覆寫佈景主題物件。可讀寫 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**傳回：**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


傳回覆寫佈景主題物件。可讀寫 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


傳回佈景主題物件。

**傳回：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


判斷 OverrideTheme 是否覆寫繼承的有效佈景主題。若要啟用 OverrideTheme 以進行覆寫，請使用 OverrideTheme.Init*() 方法。若要停用 OverrideTheme 的覆寫，請使用 OverrideTheme.Clear() 方法。唯讀布林值。

**傳回：**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


將額外的配色方案套用至投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) 物件。 |