---
title: FontData
second_title: Aspose.Slides for Android via Java API 參考
description: 代表字體定義。
type: docs
url: /zh-hant/com.aspose.slides/fontdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

代表字體定義。不可變。
## 建構式

| Constructor | Description |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | 建立具有指定字體名稱的 FontData 物件。 |
## 方法

| Method | Description |
| --- | --- |
| [getFontName()](#getFontName--) | 回傳字體名稱。 |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | 回傳字體名稱，將主題參照替換為實際使用的字體。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷兩個 FontData 實例是否相等。 |
| [hashCode()](#hashCode--) | 為特定類型提供雜湊函式，可在雜湊演算法和資料結構（如雜湊表）中使用。 |
| [toString()](#toString--) | 回傳字串表示。 |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

建立具有指定字體名稱的 FontData 物件。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | 字體名稱。 |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

回傳字體名稱。可讀寫 String。

**Returns:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

回傳字體名稱，將主題參照替換為實際使用的字體。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | 要取得主題字體名稱的主題。呼叫端需提供正確的值。見 [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Returns:**
java.lang.String - 字體名稱。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷兩個 FontData 實例是否相等。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | 要與目前 FontData 比較的 FontData。 |

**Returns:**
boolean - **true** 若指定的 FontData 等於目前的 FontData；否則，**false**。
### hashCode() {#hashCode--}
```
public int hashCode()
```

為特定類型提供雜湊函式，可在雜湊演算法和資料結構（如雜湊表）中使用。

**Returns:**
int - FontData 的雜湊碼。
### toString() {#toString--}
```
public String toString()
```

回傳字串表示。

**Returns:**
java.lang.String - 字串表示。