---
title: TextFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: TextFrame을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/textframe/
---
**상속:**
java.lang.Object

**구현된 인터페이스:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

TextFrame을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | 프레임에 있는 모든 단락의 목록을 반환합니다. |
| [getText()](#getText--) | TextFrame의 일반 텍스트를 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | TextFrame의 일반 텍스트를 가져오거나 설정합니다. |
| [getTextFrameFormat()](#getTextFrameFormat--) | 이 TextFrame 객체의 서식 개체를 반환합니다. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 포함된 하이퍼링크에 대한 쉬운 접근을 제공합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 모든 단락에서 동일한 서식을 가진 실행(run)을 합칩니다. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe)의 텍스트 콘텐츠를 문자열 배열로 분할하며, 각 요소는 프레임 내의 별도 텍스트 열에 해당합니다. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | 정규 표현식과 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 정규 표현식과 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 정규 표현식과 일치하는 모든 항목을 지정된 문자열로 교체합니다. |
| [getSlide()](#getSlide--) | TextFrame의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | TextFrame의 부모 프레젠테이션을 반환합니다. |
| [getParentShape()](#getParentShape--) | 부모 도형을 반환하거나, 부모 객체가 IShape 인터페이스를 구현하지 않으면 null을 반환합니다. 읽기 전용 [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | 부모 셀을 반환하거나, 부모 객체가 ICell 인터페이스를 구현하지 않으면 null을 반환합니다. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

프레임에 있는 모든 단락의 목록을 반환합니다. 읽기 전용 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**반환값:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

TextFrame의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**반환값:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

TextFrame의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 String.

값: 텍스트.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

이 TextFrame 객체의 서식 개체를 반환합니다. 읽기 전용 [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**반환값:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

포함된 하이퍼링크에 대한 쉬운 접근을 제공합니다. 읽기 전용 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**반환값:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

모든 단락에서 동일한 서식을 가진 실행(run)을 합칩니다.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 강조할 텍스트 샘플. |
| highlightColor | java.lang.Integer | 텍스트를 강조 표시할 색상. |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // 모든 단어 'important'를 강조
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // 모든 개별 'the' 발생을 강조
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 강조할 텍스트. |
| highlightColor | java.lang.Integer | 강조 색상. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 강조 옵션. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

[ITextFrame](../../com.aspose.slides/itextframe)의 텍스트 콘텐츠를 문자열 배열로 분할하며, 각 요소는 프레임 내의 별도 텍스트 열에 해당합니다.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // 슬라이드에서 첫 번째 도형을 가져와 ITextFrame으로 캐스팅합니다
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 텍스트 프레임 내용을 열별로 분할합니다
>      String[] columnsText = textFrame.splitTextByColumns();
>      // 각 열의 텍스트를 콘솔에 출력합니다
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
java.lang.String[] - 문자열 배열이며, 각 문자열은 [ITextFrame](../../com.aspose.slides/itextframe)의 특정 열에 대한 텍스트 콘텐츠를 나타냅니다.

--------------------

텍스트 프레임에 여러 열이 없으면 반환된 배열은 전체 텍스트를 포함하는 단일 요소를 가집니다. 빈 열은 배열에서 빈 문자열로 표시됩니다.

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

샘플 텍스트와 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다.

--------------------

> ```
> 다음 코드 샘플은 TextFrame에서 텍스트를 강조하는 방법을 보여줍니다.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 모든 단어 'important'를 강조
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // 모든 별도 'the' 발생을 강조
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 강조할 텍스트. |
| highlightColor | java.lang.Integer | 강조 색상. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 텍스트 검색 옵션 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신하기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

정규 표현식과 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // 길이가 10자 이상인 모든 단어를 강조
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| regex | java.lang.String | 강조할 텍스트를 얻기 위한 정규 표현식 텍스트. |
| highlightColor | java.lang.Integer | 강조 색상. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 강조 옵션. |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

정규 표현식과 일치하는 모든 항목을 지정된 색상으로 강조 표시합니다.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 길이가 5자 이상인 모든 단어를 강조
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 강조할 문자열을 얻기 위한 정규 표현식 java.util.regex.Pattern. |
| highlightColor | java.lang.Integer | 강조 색상. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신하기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 모든 별도 'the' 발생을 '***'로 교체
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| oldText | java.lang.String | 교체될 문자열. |
| newText | java.lang.String | oldText의 모든 발생을 교체할 문자열. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 텍스트 검색 옵션 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 교체 작업 결과를 저장하기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

정규 표현식과 일치하는 모든 항목을 지정된 문자열로 교체합니다.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5자 이상인 모든 단어를 '***'로 교체
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 교체될 문자열을 얻기 위한 정규 표현식 java.util.regex.Pattern. |
| newText | java.lang.String | 교체될 문자열의 모든 발생을 교체할 문자열. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 교체 작업 결과를 저장하기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

TextFrame의 부모 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**반환값:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

TextFrame의 부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환값:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

부모 객체가 IShape 인터페이스를 구현하지 않으면 null을 반환하고, 그렇지 않으면 부모 도형을 반환합니다. 읽기 전용 [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // 이 단언은 항상 참입니다
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환값:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

부모 객체가 ICell 인터페이스를 구현하지 않으면 null을 반환하고, 그렇지 않으면 부모 셀을 반환합니다. 읽기 전용 [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // 이 단언은 항상 참입니다
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환값:**
[ICell](../../com.aspose.slides/icell)