---
title: TextFrame
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет TextFrame.
type: docs
url: /ru/com.aspose.slides/textframe/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Представляет TextFrame.
## Методы

| Метод | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Возвращает список всех абзацев в кадре. |
| [getText()](#getText--) | Получает или устанавливает простой текст для TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Получает или устанавливает простой текст для TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Возвращает объект форматирования для данного объекта TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Обеспечивает простой доступ к содержащимся гиперссылкам. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет участки с одинаковым форматированием во всех абзацах. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Выделяет все совпадения образца текста указанным цветом. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Выделяет все совпадения образца текста указанным цветом. |
| [splitTextByColumns()](#splitTextByColumns--) | Разбивает текстовое содержимое [ITextFrame](../../com.aspose.slides/itextframe) на массив строк, где каждый элемент соответствует отдельному текстовому столбцу внутри кадра. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Выделяет все совпадения образца текста указанным цветом. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Выделяет все совпадения регулярного выражения указанным цветом. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Выделяет все совпадения регулярного выражения указанным цветом. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Заменяет все совпадения регулярного выражения указанной строкой. |
| [getSlide()](#getSlide--) | Возвращает родительский слайд TextFrame. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию TextFrame. |
| [getParentShape()](#getParentShape--) | Возвращает родительскую форму или null, если родительский объект не реализует интерфейс IShape. Только для чтения [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Возвращает родительскую ячейку или null, если родительский объект не реализует интерфейс ICell. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Возвращает список всех абзацев в кадре. Только для чтения [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Возвращаемое значение:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

Получает или устанавливает простой текст для TextFrame. Чтение/запись String.

Значение: Текст.

**Возвращаемое значение:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Получает или устанавливает простой текст для TextFrame. Чтение/запись String.

Значение: Текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

Возвращает объект форматирования для данного объекта TextFrame. Только для чтения [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Возвращаемое значение:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Возвращаемое значение:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Объединяет участки с одинаковым форматированием во всех абзацах.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Выделяет все совпадения образца текста указанным цветом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Образец текста для выделения. |
| highlightColor | java.lang.Integer | Цвет для выделения текста. |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Выделяет все совпадения образца текста указанным цветом.

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // выделение всех слов 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // выделение всех отдельных вхождений 'the'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для выделения. |
| highlightColor | java.lang.Integer | Цвет для выделения текста. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Параметры выделения. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Разбивает текстовое содержимое [ITextFrame](../../com.aspose.slides/itextframe) на массив строк, где каждый элемент соответствует отдельному текстовому столбцу внутри кадра.

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Получить первую форму на слайде и привести её к ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Разбить содержимое текстового кадра на столбцы
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Вывести текст каждого столбца в консоль
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
java.lang.String[] — массив строк, где каждая строка представляет текстовое содержимое конкретного столбца в [ITextFrame](../../com.aspose.slides/itextframe).

Если TextFrame не содержит несколько столбцов, возвращаемый массив будет иметь один элемент, содержащий весь текст. Пустые столбцы будут представлены пустыми строками в массиве.

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Выделяет все совпадения образца текста указанным цветом.

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // выделение всех слов 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // выделение всех отдельных вхождений 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для выделения. |
| highlightColor | java.lang.Integer | Цвет для выделения текста. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Параметры поиска текста [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Выделяет все совпадения регулярного выражения указанным цветом.

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // выделение всех слов длиной 10 символов и более
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.lang.String | Текст регулярного выражения для получения текста для выделения. |
| highlightColor | java.lang.Integer | Цвет для выделения текста. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Параметры выделения. |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Выделяет все совпадения регулярного выражения указанным цветом.

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // выделение всех слов длиной 5 символов и более
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Регулярное выражение java.util.regex.Pattern для получения строк для выделения. |
| highlightColor | java.lang.Integer | Цвет для выделения текста. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Заменяет все вхождения указанного текста другим указанным текстом.

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Заменить все отдельные вхождения 'the' на '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oldText | java.lang.String | Строка, которую нужно заменить. |
| newText | java.lang.String | Строка, заменяющая все вхождения oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Параметры поиска текста [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для сохранения результата операции замены [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Заменяет все совпадения регулярного выражения указанной строкой.

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Заменить все слова длиной 5 символов и более на '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Регулярное выражение java.util.regex.Pattern для получения строк, которые нужно заменить. |
| newText | java.lang.String | Строка, заменяющая все вхождения строк, которые нужно заменить. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для сохранения результата операции замены [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Возвращает родительский слайд TextFrame. Только для чтения [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию TextFrame. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Возвращает родительскую форму или null, если родительский объект не реализует интерфейс IShape. Только для чтения [IShape](../../com.aspose.slides/ishape).

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Эти утверждения всегда истинны
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

Возвращает родительскую ячейку или null, если родительский объект не реализует интерфейс ICell. Только для чтения [ICell](../../com.aspose.slides/icell).

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Эти утверждения всегда истинны
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Возвращаемое значение:**
[ICell](../../com.aspose.slides/icell)