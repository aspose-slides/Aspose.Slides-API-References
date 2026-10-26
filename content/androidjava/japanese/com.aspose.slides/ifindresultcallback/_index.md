---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 検索テキスト結果を取得するために使用されるコールバックインターフェイスです。
type: docs
url: /ja/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

検索テキスト結果を取得するために使用されるコールバックインターフェイスです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | 検出されたテキストに関するデータを受け取るコールバックメソッドです。 |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

検出されたテキストに関するデータを受け取るコールバックメソッドです。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | テキストが見つかった[ITextFrame](../../com.aspose.slides/itextframe)です。 |
| sourceText | java.lang.String | テキストが見つかった元のテキストです。 |
| foundText | java.lang.String | 見つかったテキストです。 |
| textPosition | int | 見つかったテキストの位置です。 |