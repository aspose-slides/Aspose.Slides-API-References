---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Represents a font definition.
type: docs
url: /zh-hant/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

表示字體定義。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFontName()](#getFontName--) | 返回字體名稱。 |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | 返回字體名稱，並將主題參考替換為實際使用的字體。 |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


返回字體名稱。 唯讀 String.

**返回值:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


返回字體名稱，並將主題參考替換為實際使用的字體。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | 應從中取得主題字體名稱的主題。由呼叫端提供正確的值。 |

**返回值:**
java.lang.String - 字體名稱。