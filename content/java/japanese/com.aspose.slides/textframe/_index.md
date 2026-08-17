---
title: TextFrame
second_title: Aspose.Slides for Java API リファレンス
description: TextFrame を表します。
type: docs
url: /ja/com.aspose.slides/textframe/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェース:**  
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject  
```
public final class TextFrame implements ITextFrame, IDOMObject
```

TextFrame を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | フレーム内のすべての段落のリストを返します。 |
| [getText()](#getText--) | TextFrame のプレーンテキストを取得または設定します。 |
| [setText(String value)](#setText-java.lang.String-) | TextFrame のプレーンテキストを取得または設定します。 |
| [getTextFrameFormat()](#getTextFrameFormat--) | この TextFrame オブジェクトの書式設定オブジェクトを返します。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 含まれるハイパーリンクへの簡単なアクセスを提供します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | すべての段落で同じ書式のランを結合します。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 指定された色でサンプルテキストのすべての一致箇所をハイライトします。 |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 指定された色でサンプルテキストのすべての一致箇所をハイライトします。 |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe) のテキストコンテンツを文字列配列に分割します。各要素はフレーム内の別々のテキスト列に対応します。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 指定された色でサンプルテキストのすべての一致箇所をハイライトします。 |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 指定された色で正規表現のすべての一致箇所をハイライトします。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 指定された色で正規表現のすべての一致箇所をハイライトします。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 正規表現のすべての一致箇所を指定された文字列に置換します。 |
| [getSlide()](#getSlide--) | TextFrame の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | TextFrame の親プレゼンテーションを返します。 |
| [getParentShape()](#getParentShape--) | 親オブジェクトが IShape インターフェースを実装していない場合は、親シェイプまたは null を返します。読み取り専用 [IShape](../../com.aspose.slides/ishape)。 |
| [getParentCell()](#getParentCell--) | 親オブジェクトが ICell インターフェースを実装していない場合は、親セルまたは null を返します。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject.

**戻り値:**  
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

フレーム内のすべての段落のリストを返します。読み取り専用 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)。

**戻り値:**  
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

TextFrame のプレーンテキストを取得または設定します。読み書き String。

値: テキスト。

**戻り値:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

TextFrame のプレーンテキストを取得または設定します。読み書き String。

値: テキスト。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

この TextFrame オブジェクトの書式設定オブジェクトを返します。読み取り専用 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**戻り値:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

含まれるハイパーリンクへの簡単なアクセスを提供します。読み取り専用 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**戻り値:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

すべての段落で同じ書式のランを結合します。

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

指定された色でサンプルテキストのすべての一致箇所をハイライトします。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | ハイライトするテキストのサンプル。 |
| highlightColor | java.awt.Color | テキストをハイライトする色。 |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

指定された色でサンプルテキストのすべての一致箇所をハイライトします。

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // すべての単語 'important' をハイライト
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // すべての個別の 'the' の出現箇所をハイライト
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | ハイライトするテキスト。 |
| highlightColor | java.awt.Color | ハイライトする色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ハイライトオプション。 |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

[ITextFrame](../../com.aspose.slides/itextframe) のテキストコンテンツを文字列配列に分割します。各要素はフレーム内の別々のテキスト列に対応します。

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // スライド上の最初のシェイプを取得し、ITextFrame にキャストします
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // テキストフレームのコンテンツを列に分割します
>      String[] columnsText = textFrame.splitTextByColumns();
>      // 各列のテキストをコンソールに出力します
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**  
java.lang.String[] - 文字列配列 - 各文字列は [ITextFrame](../../com.aspose.slides/itextframe) 内の特定の列のテキストコンテンツを表します。

--------------------

テキストフレームに複数列が含まれていない場合、返される配列は全文テキストを含む単一要素となります。空の列は配列内で空文字列として表されます。

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

指定された色でサンプルテキストのすべての一致箇所をハイライトします。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // すべての単語 'important' をハイライト
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // すべての個別の 'the' の出現箇所をハイライト
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | ハイライトするテキスト。 |
| highlightColor | java.awt.Color | ハイライトする色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | テキスト検索オプション [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

指定された色で正規表現のすべての一致箇所をハイライトします。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // 10文字以上のすべての単語をハイライト
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | java.lang.String | ハイライトする正規表現のテキスト。 |
| highlightColor | java.awt.Color | ハイライトする色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | ハイライトオプション。 |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

指定された色で正規表現のすべての一致箇所をハイライトします。

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

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | ハイライトする文字列を取得する正規表現 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | ハイライトする色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 検索結果を受け取るコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

指定されたテキストのすべての出現箇所を別の指定テキストに置換します。

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 'the' のすべての個別の出現箇所を '***' に置換
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| oldText | java.lang.String | 置換される文字列。 |
| newText | java.lang.String | oldText のすべての出現箇所を置換する文字列。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | テキスト検索オプション [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 置換操作結果を保存するコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

正規表現のすべての一致箇所を指定された文字列に置換します。

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5文字以上のすべての単語を '***' に置換
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 置換される文字列を取得する正規表現 java.util.regex.Pattern。 |
| newText | java.lang.String | 置換される文字列を置換する文字列。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 置換操作結果を保存するコールバックオブジェクト [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

TextFrame の親スライドを返します。読み取り専用 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**戻り値:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

TextFrame の親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

親オブジェクトが IShape インターフェースを実装していない場合は、親シェイプまたは null を返します。読み取り専用 [IShape](../../com.aspose.slides/ishape)。

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
public final ICell getParentCell()
```

親オブジェクトが ICell インターフェースを実装していない場合は、親セルまたは null を返します。読み取り専用 [ICell](../../com.aspose.slides/icell)。

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