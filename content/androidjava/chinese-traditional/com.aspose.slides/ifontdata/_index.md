---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: 表示字體定義。
type: docs
url: /zh-hant/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

表示字體定義。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFontName()](#getFontName--) | 傳回字體名稱。 |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | 傳回字體名稱，將主題參照取代為實際使用的字體。 |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

傳回字體名稱。唯讀 String.

**傳回：**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

傳回字體名稱，將主題參照取代為實際使用的字體。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | 應取得主題化字體名稱的主題。呼叫端需提供正確的值。 |

**傳回：**
java.lang.String - 字體名稱。