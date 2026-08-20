---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
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
| [getLevel(int index)](#getLevel-int-) | 返回有效樣式的層級。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 返回有效的預設段落屬性。 |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


返回有效樣式的層級。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 層級的零基索引。 必須位於 0..8 的區間內。 |

**傳回值:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - 有效層級 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 的格式設定。

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


返回有效的預設段落屬性。 唯讀 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)。

**傳回值:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)