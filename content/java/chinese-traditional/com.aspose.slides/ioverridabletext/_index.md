---
title: IOverridableText
second_title: Aspose.Slides for Java API 參考
description: 表示圖表可覆寫的文字。
type: docs
url: /zh-hant/com.aspose.slides/ioverridabletext/
---
**所有已實作的介面：**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

表示圖表可覆寫的文字。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | 可以包含豐富格式的文字。 |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | 使用參數 "text" 中的文字初始化 TextFrameForOverriding。 |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

可以包含豐富格式的文字。如果此屬性不為 null，則此格式化文字值會覆寫自動產生的文字。自動產生的文字是資料標籤、值軸的顯示單位標籤、軸標題、圖表標題、趨勢線標籤的隱含屬性。自動產生的文字會使用 IFormattedTextContainer.TextFormat 屬性進行格式化。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**傳回:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

使用參數 "text" 中的文字初始化 TextFrameForOverriding。如果 TextFrameForOverriding 已經初始化，則僅變更其文字。

**參數:**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 新 TextFrameForOverriding 的文字。 |

**傳回:**
[ITextFrame](../../com.aspose.slides/itextframe) - 文字框 [ITextFrame](../../com.aspose.slides/itextframe)