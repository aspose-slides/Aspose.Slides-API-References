---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 指定在 Markdown 匯出時，應如何處理重複的普通空格字元。
type: docs
url: /zh-hant/com.aspose.slides/handlerepeatedspaces/
---
**繼承:** 
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

指定在 Markdown 匯出時，如何處理重複的普通空格字元。

## 欄位

| 欄位 | 說明 |
| --- | --- |
| [None](#None) | 所有空格皆保留為普通空格字元，且不作任何變更。 |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | 將兩個或以上連續的普通空格序列，轉換為交替的普通空格字元與不斷行空格實體（NBSP）。 |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | 將兩個或以上連續的普通空格序列，保留第一個空格為普通空格字元，並將其餘所有空格替換為不斷行空格實體（NBSP）。 |
### None {#None}
```
public static final int None
```

所有空格皆保留為普通空格字元，且不作任何變更。未套用任何轉換，連續多個空格將如實匯出。

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

將兩個或以上連續的普通空格序列，轉換為交替的普通空格字元與不斷行空格實體（NBSP）。第一個空格始終保留為普通空格。

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

將兩個或以上連續的普通空格序列，保留第一個空格為普通空格字元，並將其餘所有空格替換為不斷行空格實體（NBSP）。