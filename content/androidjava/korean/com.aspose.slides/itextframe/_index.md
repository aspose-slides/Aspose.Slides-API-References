---
title: ITextFrame
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: TextFrame을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itextframe/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

TextFrame을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | 프레임의 모든 단락 목록을 반환합니다. |
| [getText()](#getText--) | TextFrame의 일반 텍스트를 가져오거나 설정합니다. |
| [setText(String value)](#setText-java.lang.String-) | TextFrame의 일반 텍스트를 가져오거나 설정합니다. |
| [getTextFrameFormat()](#getTextFrameFormat--) | 이 TextFrame 객체의 형식 지정 개체를 반환합니다. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 포함된 하이퍼링크에 손쉽게 액세스합니다. |
| [getParentShape()](#getParentShape--) | 부모 객체가 IShape 인터페이스를 구현하지 않을 경우 부모 쉐이프 또는 null을 반환합니다. 읽기 전용 [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | 부모 객체가 ICell 인터페이스를 구현하지 않을 경우 부모 셀 또는 null을 반환합니다. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 모든 단락에서 동일한 서식의 실행을 결합합니다. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | 지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조합니다. |
| [splitTextByColumns()](#splitTextByColumns--) | [ITextFrame](../../com.aspose.slides/itextframe)의 텍스트 내용을 문자열 배열로 분할하며, 각 요소는 프레임 내의 개별 텍스트 열에 해당합니다. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | 지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조합니다. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조합니다. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 지정된 색상으로 정규식과 일치하는 모든 항목을 강조합니다. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | 지정된 색상으로 정규식과 일치하는 모든 항목을 강조합니다. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 정규식과 일치하는 모든 항목을 지정된 문자열로 교체합니다. |
### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```


프레임의 모든 단락 목록을 반환합니다. 읽기 전용 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**반환:**  
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```


TextFrame의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 문자열.

값: 텍스트.

**반환:**  
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


TextFrame의 일반 텍스트를 가져오거나 설정합니다. 읽기/쓰기 문자열.

값: 텍스트.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```


이 TextFrame 객체의 형식 지정 개체를 반환합니다. 읽기 전용 [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**반환:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


포함된 하이퍼링크에 손쉽게 액세스합니다. 읽기 전용 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**반환:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```


부모 객체가 IShape 인터페이스를 구현하지 않을 경우 부모 쉐이프 또는 null을 반환합니다. 읽기 전용 [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // These assertions are always true
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**반환:**  
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```


부모 객체가 ICell 인터페이스를 구현하지 않을 경우 부모 셀 또는 null을 반환합니다. 읽기 전용 [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // 이 단언은 항상 true입니다
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**반환:**  
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


모든 단락에서 동일한 서식의 실행을 결합합니다.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```


지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 강조할 텍스트. |
| highlightColor | java.lang.Integer | 텍스트를 강조할 색상. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```


[ITextFrame](../../com.aspose.slides/itextframe)의 텍스트 내용을 문자열 배열로 분할하며, 각 요소는 프레임 내의 개별 텍스트 열에 해당합니다.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // 슬라이드에서 첫 번째 도형을 가져와 ITextFrame으로 캐스팅합니다
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 텍스트 프레임 내용을 열로 분할합니다
>      String[] columnsText = textFrame.splitTextByColumns();
>      // 각 열의 텍스트를 콘솔에 출력합니다
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**  
java.lang.String[] - 각 문자열이 [ITextFrame](../../com.aspose.slides/itextframe)의 특정 열에 해당하는 텍스트 내용을 나타내는 문자열 배열.

--------------------

텍스트 프레임에 여러 열이 포함되어 있지 않으면 반환된 배열에는 전체 텍스트를 포함하는 단일 요소가 있습니다. 빈 열은 배열에서 빈 문자열로 표시됩니다.
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```


지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 강조할 텍스트. |
| highlightColor | java.lang.Integer | 텍스트를 강조할 색상. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 강조 옵션. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


지정된 색상으로 샘플 텍스트와 일치하는 모든 항목을 강조합니다.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 모든 'important' 단어 강조
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // 모든 별도 'the' 발생 강조
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 강조할 텍스트. |
| highlightColor | java.lang.Integer | 텍스트를 강조할 색상. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 텍스트 검색 옵션 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신하기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```


지정된 색상으로 정규식과 일치하는 모든 항목을 강조합니다.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5자 이상인 모든 단어를 강조
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 강조할 문자열을 얻기 위한 정규식 java.util.regex.Pattern. |
| highlightColor | java.lang.Integer | 텍스트를 강조할 색상. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신하기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```


지정된 색상으로 정규식과 일치하는 모든 항목을 강조합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | java.lang.String | 강조할 텍스트를 얻기 위한 정규식 텍스트. |
| highlightColor | java.lang.Integer | 텍스트를 강조할 색상. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 강조 옵션. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


지정된 텍스트의 모든 발생을 다른 지정된 텍스트로 교체합니다.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 모든 별도 'the' 발생을 '***'으로 교체합니다
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oldText | java.lang.String | 교체될 문자열. |
| newText | java.lang.String | oldText의 모든 발생을 교체할 문자열. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 텍스트 검색 옵션 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신하기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


정규식과 일치하는 모든 항목을 지정된 문자열로 교체합니다.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 5자 이상인 모든 단어를 '***'으로 교체합니다
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 교체할 문자열을 얻기 위한 정규식 java.util.regex.Pattern. |
| newText | java.lang.String | 교체될 문자열의 모든 발생을 교체할 문자열. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 검색 결과를 수신하기 위한 콜백 객체 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |