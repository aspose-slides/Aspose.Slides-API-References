---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for Java API 參考
description: 指定在 Markdown 匯出時，如何處理重複的普通空格字符。
type: docs
url: /zh-hant/com.aspose.slides/handlerepeatedspaces/
---
**繼承：**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

指定在 Markdown 匯出時，如何處理重複的普通空格字元。
## 欄位

| 欄位 | 描述 |
| --- | --- |
| [None](#None) | 所有空格皆以普通空格字元保留，未作任何變更。 |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | 將兩個或以上連續的普通空格字元序列，以普通空格與不換行空格實體 NBSP 交替的方式進行轉換。 |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | 將兩個或以上連續的普通空格字元序列，以保留第一個空格為普通空格字元，並將其餘空格替換為不換行空格實體 NBSP 的方式進行轉換。 |
### None {#None}
```
public static final int None
```


所有空格皆以普通空格字元保留，未作任何變更。未套用任何轉換，且多個連續空格將照原樣匯出。

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```


將兩個或以上連續的普通空格字元序列，以普通空格與不換行空格實體 NBSP 交替的方式進行轉換。第一個空格始終保留為普通空格。

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```


將兩個或以上連續的普通空格字元序列，以保留第一個空格為普通空格字元，並將其餘空格替換為不換行空格實體 NBSP 的方式進行轉換。