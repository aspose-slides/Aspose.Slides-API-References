---
title: BaseOverrideThemeManager
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 提供存取不同類型已覆寫佈景主題之類別的基礎類別。
type: docs
url: /zh-hant/com.aspose.slides/baseoverridethememanager/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**已實作的介面:**  
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

基底類別，用於提供存取不同類型已覆寫佈景主題的類別。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | 返回覆寫的佈景主題物件。 |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | 返回覆寫的佈景主題物件。 |
| [createThemeEffective()](#createThemeEffective--) | 返回佈景主題物件。 |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 判斷 OverrideTheme 是否覆寫繼承的有效佈景主題。 |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | 將額外的色彩配置套用至投影片。 |

### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

返回覆寫的佈景主題物件。可讀寫 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**返回值:**  
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)

### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

返回覆寫的佈景主題物件。可讀寫 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

返回佈景主題物件。

**返回值:**  
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

判斷 OverrideTheme 是否覆寫繼承的有效佈景主題。若要啟用 OverrideTheme 進行覆寫，請使用 OverrideTheme.Init*() 方法。若要停用 OverrideTheme 的覆寫，請使用 OverrideTheme.Clear() 方法。唯讀布林值。

**返回值:**  
boolean

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

將額外的色彩配置套用至投影片。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | 此 [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) 物件。 |