---
title: IOverrideThemeManager
second_title: Aspose.Slides for Android via Java API 參考
description: 提供對不同類型被覆寫主題的存取。
type: docs
url: /zh-hant/com.aspose.slides/ioverridethememanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

提供對不同類型被覆寫主題的存取。

## 方法

| Method | Description |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | 判斷 OverrideTheme 是否覆寫繼承的有效主題。 |
| [getOverrideTheme()](#getOverrideTheme--) | 返回覆寫的主題物件。 |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | 返回覆寫的主題物件。 |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

判斷 OverrideTheme 是否覆寫繼承的有效主題。若要啟用 OverrideTheme 以進行覆寫，請使用 OverrideTheme.Init\*() 方法。若要停用 OverrideTheme 的覆寫，請使用 OverrideTheme.Clear() 方法。唯讀布林值。

**傳回值:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

返回覆寫的主題物件。讀寫 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**傳回值:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

返回覆寫的主題物件。讀寫 [IOverrideTheme](../../com.aspose.slides/ioverridetheme)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |