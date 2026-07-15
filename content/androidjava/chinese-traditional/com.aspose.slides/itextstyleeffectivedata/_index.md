---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 不可變的物件，包含有效的文字樣式屬性。
type: docs
url: /zh-hant/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

不可變的物件，包含有效的文字樣式屬性。

--------------------

此介面與 [ITextStyle](../../com.aspose.slides/itextstyle) 介面一起使用，以返回套用繼承後的有效格式設定值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | 傳回有效樣式的層級。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 傳回有效的預設段落屬性。 |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

傳回有效樣式的層級。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 層級的零基索引。必須在 0..8 範圍內。 |

**傳回值:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - 層級 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 的有效格式設定。

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

傳回有效的預設段落屬性。唯讀 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)。

**傳回值:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)