---
title: IOverrideThemeManager
second_title: Aspose.Slides for Java API 參考
description: 提供對不同類型的覆寫主題的存取。
type: docs
url: /zh-hant/com.aspose.slides/ioverridethememanager/
---
**所有已實作的介面：**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

提供對不同類型的覆寫主題的存取。
## 方法

| 方法 | 說明 |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 判斷 OverrideTheme 是否覆寫繼承的有效主題。 |
| [getOverrideTheme()](#getOverrideTheme--) | 傳回覆寫的主題物件。 |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | 傳回覆寫的主題物件。 |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

判斷 OverrideTheme 是否覆寫繼承的有效主題。要啟用 OverrideTheme 以進行覆寫，請使用 OverrideTheme.Init\*() 方法。要停用 OverrideTheme 的覆寫，請使用 OverrideTheme.Clear() 方法。唯讀布林值。

**傳回：**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

傳回覆寫的主題物件。可讀寫 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**傳回：**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

傳回覆寫的主題物件。可讀寫 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |