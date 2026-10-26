---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /ja/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

検索テキスト結果を取得するために使用されるコールバックインターフェイス。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | 見つかったテキストに関するデータを受け取るコールバックメソッドです。 |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

見つかったテキストに関するデータを受け取るコールバックメソッドです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | テキストが見つかった[ITextFrame](../../com.aspose.slides/itextframe)。 |
| sourceText | java.lang.String | テキストが見つかった元テキスト。 |
| foundText | java.lang.String | 見つかったテキスト。 |
| textPosition | int | 見つかったテキストの位置。 |