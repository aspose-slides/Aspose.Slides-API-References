---
title: MasterThemeManager
second_title: Aspose.Slides for Android via Java API 參考文件
description: 提供對簡報母版主題的存取。
type: docs
url: /zh-hant/com.aspose.slides/masterthememanager/
---
**繼承：**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**所有實作的介面：**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

提供對簡報母版主題的存取。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | 回傳覆寫的主題物件。 |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | 回傳覆寫的主題物件。 |
| [createThemeEffective()](#createThemeEffective--) | 回傳主題物件。 |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 判斷 OverrideTheme 是否覆寫繼承的有效主題 (Presentation.MasterTheme)。 |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | 判斷 OverrideTheme 是否覆寫繼承的有效主題 (Presentation.MasterTheme)。 |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | 將額外的色彩配置套用至投影片。 |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

回傳覆寫的主題物件。讀/寫 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**回傳值：**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

回傳覆寫的主題物件。讀/寫 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

回傳主題物件。

**回傳值：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

判斷 OverrideTheme 是否覆寫繼承的有效主題 (Presentation.MasterTheme)。讀/寫 boolean。

**回傳值：**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

判斷 OverrideTheme 是否覆寫繼承的有效主題 (Presentation.MasterTheme)。讀/寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

將額外的色彩配置套用至投影片。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) 物件。 |