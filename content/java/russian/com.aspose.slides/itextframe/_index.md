---
title: ITextFrame
second_title: Справочник API Aspose.Slides для Java
description: Представляет TextFrame.
type: docs
url: /ru/com.aspose.slides/itextframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Represents a TextFrame.
## Методы

| Метод | Описание |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Возвращает список всех абзацев во фрейме. |
| [getText()](#getText--) | Получает или задает простой текст для TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает простой текст для TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Возвращает объект форматирования для этого объекта TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Обеспечивает простой доступ к содержащимся гиперссылкам. |
| [getParentShape()](#getParentShape--) | Возвращает родительскую форму или null, если родительский объект не реализует интерфейс IShape. Только для чтения [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | Получает прямоугольник текста, определенный геометрией родительской формы. |
| [getParentCell()](#getParentCell--) | Возвращает родительскую ячейку или null, если родительский объект не реализует интерфейс ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет участки с одинаковым форматированием во всех абзацах. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Подсвечивает все совпадения образца текста указанным цветом. |
| [splitTextByColumns()](#splitTextByColumns--) | Разбивает текстовое содержимое [ITextFrame](../../com.aspose.slides/itextframe) на массив строк, где каждый элемент соответствует отдельной колонке текста во фрейме. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Подсвечивает все совпадения образца текста указанным цветом. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Подсвечивает все совпадения образца текста указанным цветом. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Подсвечивает все совпадения регулярного выражения указанным цветом. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Подсвечивает все совпадения регулярного выражения указанным цветом. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Заменяет все совпадения регулярного выражения указанной строкой. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Возвращает список всех абзацев во фрейме. Только для чтения [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Возвращает:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

Получает или задает простой текст для TextFrame. Чтение/запись String.

Значение: Текст.

**Возвращает:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Получает или задает простой текст для TextFrame. Чтение/запись String.

Значение: Текст.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Возвращает объект форматирования для этого объекта TextFrame. Только для чтения [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Возвращает:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Обеспечивает простой доступ к содержащимся гиперссылкам. Только для чтения [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Возвращает:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

Возвращает родительскую форму или null, если родительский объект не реализует интерфейс IShape. Только для чтения [IShape](../../com.aspose.slides/ishape).

--------------------

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


**Возвращает:**
[IShape](../../com.aspose.slides/ishape)

### getTextRect() {#getTextRect--}
```
public abstract Rectangle2D.Float getTextRect()
```

Получает прямоугольник текста, определенный геометрией родительской формы.

**Возвращает:**
java.awt.geom.Rectangle2D.Float — объект java.awt.geom.Rectangle2D.Float, определяющий область текста.

--------------------

Координаты прямоугольника заданы относительно левого верхнего угла родительской формы.

### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

Возвращает родительскую ячейку или null, если родительский объект не реализует интерфейс ICell. Только для чтения [ICell](../../com.aspose.slides/icell).

--------------------

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


**Возвращает:**
[ICell](../../com.aspose.slides/icell)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Объединяет участки с одинаковым форматированием во всех абзацах.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Подсвечивает все совпадения образца текста указанным цветом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для подсветки. |
| highlightColor | java.awt.Color | Цвет для подсветки текста. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Разбивает текстовое содержимое [ITextFrame](../../com.aspose.slides/itextframe) на массив строк, где каждый элемент соответствует отдельной колонке текста во фрейме.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Получить первую форму на слайде и привести её к ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Разбить содержимое текстового фрейма на колонки
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Вывести текст каждой колонки в консоль
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
java.lang.String[] — массив строк, где каждая строка представляет собой текстовое содержимое определённого столбца в [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Если текстовый фрейм не содержит нескольких колонок, возвращаемый массив будет иметь один элемент, содержащий весь текст. Пустые колонки будут представлены пустыми строками в массиве.

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

Подсвечивает все совпадения образца текста указанным цветом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для подсветки. |
| highlightColor | java.awt.Color | Цвет для подсветки текста. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Параметры подсветки. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Подсвечивает все совпадения образца текста указанным цветом.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // подсветка всех слов 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // подсветка всех отдельных вхождений 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для подсветки. |
| highlightColor | java.awt.Color | Цвет для подсветки текста. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Параметры поиска текста [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Подсвечивает все совпадения регулярного выражения указанным цветом.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // подсветка всех слов длиной 5 символов и более
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Регулярное выражение java.util.regex.Pattern для получения строк для подсветки. |
| highlightColor | java.awt.Color | Цвет для подсветки текста. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

Подсвечивает все совпадения регулярного выражения указанным цветом.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.lang.String | Текст регулярного выражения для получения текста для подсветки. |
| highlightColor | java.awt.Color | Цвет для подсветки текста. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Параметры подсветки. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Заменяет все вхождения указанного текста другим указанным текстом.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
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
| oldText | java.lang.String | Строка, подлежащая замене. |
| newText | java.lang.String | Строка, заменяющая все вхождения oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Параметры поиска текста [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Заменяет все совпадения регулярного выражения указанной строкой.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
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
| regex | java.util.regex.Pattern | Регулярное выражение java.util.regex.Pattern для получения строк для замены. |
| newText | java.lang.String | Строка, заменяющая все вхождения строк, подлежащих замене. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |