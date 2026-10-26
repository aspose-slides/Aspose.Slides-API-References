---
title: IMasterThemeManager
second_title: Aspose.Slides Java API 參考
description: 提供對簡報母版主題的存取。
type: docs
url: /zh-hant/com.aspose.slides/imasterthememanager/
---
**所有已實作的介面:**  
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IMasterThemeManager extends IThemeManager
```

提供對簡報母版主題的存取。  
## 方法

| 方法 | 說明 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 判斷 OverrideTheme 是否覆寫繼承的有效主題 (Presentation.MasterTheme) 或未。 |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | 判斷 OverrideTheme 是否覆寫繼承的有效主題 (Presentation.MasterTheme) 或未。 |
| [getOverrideTheme()](#getOverrideTheme--) | 回傳覆寫的主題物件。 |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | 回傳覆寫的主題物件。 |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

判斷 OverrideTheme 是否覆寫繼承的有效主題 (Presentation.MasterTheme) 或未。可讀寫 boolean。

**回傳:**  
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public abstract void setOverrideThemeEnabled(boolean value)
```

判斷 OverrideTheme 是否覆寫繼承的有效主題 (Presentation.MasterTheme) 或未。可讀寫 boolean。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IMasterTheme getOverrideTheme()
```

回傳覆寫的主題物件。可讀寫 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**回傳:**  
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public abstract void setOverrideTheme(IMasterTheme value)
```

回傳覆寫的主題物件。可讀寫 [IMasterTheme](../../com.aspose.slides/imastertheme)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  