---
title: ITextFrame
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: TextFrame を表します。
type: docs
url: /ja/com.aspose.slides/itextframe/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

TextFrame を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | フレーム内のすべての段落のリストを返します。 |
| [getText()](#getText--) | TextFrame のプレーンテキストを取得または設定します。 |
| [setText(String value)](#setText-java.lang.String-) | TextFrame のプレーンテキストを取得または設定します。 |
| [getTextFrameFormat()](#getTextFrameFormat--) | この TextFrame オブジェクトの書式設定オブジェクトを返します。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 含まれるハイパーリンクへの簡単なアクセスを提供します。 |
| [getParentShape()](#getParentShape--) | 親シェイプを返すか、親オブジェクトが IShape インターフェイスを実装していない場合は null を返します。 読み取り専用 [IShape](../../com.aspose.slides/ishape)。 |
| [getParentCell()](#getParentCell--) | 親セルを返すか、親オブジェクトが ICell インターフェイスを実装していない場合は null を返します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | すべての段落で同じ書式設定のランを結合します。 |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe) のテキストコンテンツを文字列配列に分割し、各要素はフレーム内の別々のテキスト列に対応します。 |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 正規表現のすべての一致箇所を指定された色でハイライトします。 |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | 正規表現のすべての一致箇所を指定された色でハイライトします。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 指定されたテキストのすべての出現箇所を別の指定テキストに置き換えます。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 正規表現のすべての一致箇所を指定された文字列に置き換えます。 |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

フレーム内のすべての段落のリストを返します。 読み取り専用 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)。

**戻り値:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```

TextFrame のプレーンテキストを取得または設定します。 読み書き String.

値: テキスト。

**戻り値:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

TextFrame のプレーンテキストを取得または設定します。 読み書き String.

値: テキスト。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

この TextFrame オブジェクトの書式設定オブジェクトを返します。 読み取り専用 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**戻り値:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

含まれるハイパーリンクへの簡単なアクセスを提供します。 読み取り専用 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**戻り値:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

親シェイプを返すか、親オブジェクトが IShape インターフェイスを実装していない場合は null を返します。 読み取り専用 [IShape](../../com.aspose.slides/ishape)。

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // これらのアサーションは常に真です
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

親セルを返すか、親オブジェクトが ICell インターフェイスを実装していない場合は null を返します。 読み取り専用 [ICell](../../com.aspose.slides/icell)。

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // これらのアサーションは常に真です
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**戻り値:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

すべての段落で同じ書式設定のランを結合します。

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

サンプルテキストのすべての一致箇所を指定された色でハイライトします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | ハイライトするテキスト。 |
| highlightColor | java.lang.Integer | テキストをハイライトする色。 |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

[ITextFrame](../../com.aspose.slides/itextframe) のテキストコンテンツを文字列配列に分割し、各要素はフレーム内の別々のテキスト列に対応します。

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // スライド上の最初のシェイプを取得し、ITextFrame にキャストします
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // テキストフレームの内容を列に分割します
>      String[] columnsText = textFrame.splitTextByColumns();
>      // 各列のテキストをコンソールに出力します
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
java.lang.String[] - 各文字列が [ITextFrame](../../com.aspose.slides/itextframe) の特定の列のテキストコンテンツを表す文字列配列。

--------------------

テキストフレームに複数列が含まれていない場合、返される配列は単一要素で全文テキストを含みます。 空の列は配列内で空文字列として表されます。
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

サンプルテキストのすべての一致箇所を指定された色でハイライトします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | ハイライトするテキスト。 |
| highlightColor | java.lang.Integer | テキストをハイライトする色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ハイライトオプション。 |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

サンプルテキストのすべての一致箇所を指定された色でハイライトします。

--------------------

> ```
> 以下のコードサンプルは TextFrame のテキストをハイライトする方法を示しています。
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 'important' のすべての単語をハイライト
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // 'the' のすべての個別の出現をハイライト
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | ハイライトするテキスト。 |
| highlightColor | java.lang.Integer | テキストをハイライトする色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | テキスト検索オプション [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るためのコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

正規表現のすべての一致箇所を指定された色でハイライトします。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5文字以上のすべての単語をハイライト
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | ハイライト対象文字列を取得する正規表現 java.util.regex.Pattern。 |
| highlightColor | java.lang.Integer | テキストをハイライトする色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るためのコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

正規表現のすべての一致箇所を指定された色でハイライトします。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| regex | java.lang.String | ハイライト対象テキストを取得する正規表現文字列。 |
| highlightColor | java.lang.Integer | テキストをハイライトする色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ハイライトオプション。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

指定されたテキストのすべての出現箇所を別の指定テキストに置き換えます。

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // すべての個別の 'the' の出現を '***' に置き換えます
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| oldText | java.lang.String | 置換される文字列。 |
| newText | java.lang.String | oldText のすべての出現箇所を置換する文字列。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | テキスト検索オプション [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るためのコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

正規表現のすべての一致箇所を指定された文字列に置き換えます。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5文字以上のすべての単語を '***' に置き換えます
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 置換対象文字列を取得する正規表現 java.util.regex.Pattern。 |
| newText | java.lang.String | 置換対象文字列のすべての出現箇所を置換する文字列。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るためのコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |