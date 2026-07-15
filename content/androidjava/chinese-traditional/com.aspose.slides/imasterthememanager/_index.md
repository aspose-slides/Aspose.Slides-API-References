---
title: IMasterThemeManager
second_title: Aspose.Slides for Android via Java API 參考
description: 提供對簡報母版主題的存取。
type: docs
url: /zh-hant/com.aspose.slides/imasterthememanager/
---
**已實作的介面:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IMasterThemeManager extends IThemeManager
```

提供對簡報母版主題的存取。
## 方法

| 方法 | 描述 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 確定 OverrideTheme 是否覆寫繼承的有效主題（Presentation.MasterTheme）。 |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | 確定 OverrideTheme 是否覆寫繼承的有效主題（Presentation.MasterTheme）。 |
| [getOverrideTheme()](#getOverrideTheme--) | 傳回覆寫的主題物件。 |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | 傳回覆寫的主題物件。 |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


確定 OverrideTheme 是否覆寫繼承的有效主題（Presentation.MasterTheme）。 可讀寫 boolean。

**返回值:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public abstract void setOverrideThemeEnabled(boolean value)
```


確定 OverrideTheme 是否覆寫繼承的有效主題（Presentation.MasterTheme）。 可讀寫 boolean。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IMasterTheme getOverrideTheme()
```


傳回覆寫的主題物件。 可讀寫 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**返回值:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public abstract void setOverrideTheme(IMasterTheme value)
```


傳回覆寫的主題物件。 可讀寫 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**參數:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |