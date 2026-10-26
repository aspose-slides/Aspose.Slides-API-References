---
title: FontData
second_title: Aspose.Slides for Java API 參考
description: 表示字型定義。
type: docs
url: /zh-hant/com.aspose.slides/fontdata/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

表示字型定義。不可變。
## 建構式

| 建構子 | 說明 |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | 建立具有指定字型名稱的新 FontData 物件。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFontName()](#getFontName--) | 傳回字型名稱。 |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | 傳回字型名稱，將主題參考取代為實際使用的字型。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷兩個 FontData 實例是否相等。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式，可用於雜湊演算法和類似雜湊表的資料結構。 |
| [toString()](#toString--) | 傳回字串表示。 |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

建立具有指定字型名稱的新 FontData 物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| fontName | java.lang.String | 字型名稱。 |
### getFontName() {#getFontName--}
```
public final String getFontName()
```

傳回字型名稱。讀/寫 String。

**傳回:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

傳回字型名稱，將主題參考取代為實際使用的字型。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | 應從此主題取得主題字型名稱。呼叫端需提供正確的值。參見 [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**傳回:**
java.lang.String - 字型名稱。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷兩個 FontData 實例是否相等。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 用於與當前 FontData 比較的 FontData。 |

**傳回:**
boolean - **true** 若指定的 FontData 等於當前的 FontData；否則為 **false**。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式，可用於雜湊演算法和類似雜湊表的資料結構。

**傳回:**
int - FontData 的雜湊碼。
### toString() {#toString--}
```
public String toString()
```

傳回字串表示。

**傳回:**
java.lang.String - 字串表示。