---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /zh-hant/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

用於取得搜尋文字結果的回呼介面。
## 方法

| 方法 | 描述 |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | 接收關於找到的文字資料的回呼方法。 |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


接收關於找到的文字資料的回呼方法。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 在 [ITextFrame](../../com.aspose.slides/itextframe) 中找到的文字。 |
| sourceText | java.lang.String | 找到文字的來源文字。 |
| foundText | java.lang.String | 找到的文字。 |
| textPosition | int | 找到文字的位置。 |