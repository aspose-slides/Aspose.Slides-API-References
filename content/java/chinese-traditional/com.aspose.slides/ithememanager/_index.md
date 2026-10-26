---
title: IThemeManager
second_title: Aspose.Slides for Java API 參考
description: 表示主題屬性。
type: docs
url: /zh-hant/com.aspose.slides/ithememanager/
---```
public interface IThemeManager
```

表示主題屬性。
## 方法

| 方法 | 說明 |
| --- | --- |
| [createThemeEffective()](#createThemeEffective--) | 傳回 Theme 物件。 |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | 將 extra color scheme 套用至投影片。 |
### createThemeEffective() {#createThemeEffective--}
```
public abstract IThemeEffectiveData createThemeEffective()
```


傳回 Theme 物件。

**傳回：**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Theme 物件 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public abstract void applyColorScheme(IExtraColorScheme scheme)
```


將 extra color scheme 套用至投影片。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | 額外色彩配置 [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) |