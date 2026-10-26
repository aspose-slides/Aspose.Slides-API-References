---
title: IFindResultCallback
second_title: Aspose.Slides for Java API 參考
description: 用於取得搜尋文字結果的回呼介面。
type: docs
url: /zh-hant/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

用於取得搜尋文字結果的回呼介面。
## 方法

| 方法 | 說明 |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | 接收有關已找到文字資料的回呼方法。 |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


接收有關已找到文字資料的回呼方法。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 找到文字的 [ITextFrame](../../com.aspose.slides/itextframe)。 |
| sourceText | java.lang.String | 在其中找到文字的來源文字。 |
| foundText | java.lang.String | 找到的文字。 |
| textPosition | int | 已找到文字的位置。 |