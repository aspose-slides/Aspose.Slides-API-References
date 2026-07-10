---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API 参考
description: 用于获取搜索文本结果的回调接口。
type: docs
url: /zh/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

用于获取搜索文本结果的回调接口。
## 方法

| 方法 | 描述 |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | 接收有关找到的文本数据的回调方法。 |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

接收有关找到的文本数据的回调方法。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 在其中找到文本的 [ITextFrame](../../com.aspose.slides/itextframe)。 |
| sourceText | java.lang.String | 在其中找到文本的源文本。 |
| foundText | java.lang.String | 找到的文本。 |
| textPosition | int | 找到的文本的位置。 |