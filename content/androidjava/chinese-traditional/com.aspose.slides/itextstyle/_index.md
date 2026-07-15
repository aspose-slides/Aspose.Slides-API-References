---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: 文本樣式格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

文本樣式格式屬性。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | 如果樣式層級存在則返回它，否則返回 null。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 預設段落屬性。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效文本樣式格式化資料。 |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

如果樣式層級存在則返回它，否則返回 null。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 層級的零基索引。必須在 0..8 範圍內。 |

**返回值:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 第 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 級的格式化。

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

預設段落屬性。唯讀 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**返回值:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

取得套用繼承後的有效文本樣式格式化資料。

**返回值:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - 一個 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。