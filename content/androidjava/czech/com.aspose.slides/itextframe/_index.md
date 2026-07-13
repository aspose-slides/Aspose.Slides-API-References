---
title: ITextFrame
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje TextFrame.
type: docs
url: /cs/com.aspose.slides/itextframe/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Reprezentuje TextFrame.
## Metody

| Metoda | Popis |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Vrací seznam všech odstavců v rámečku. |
| [getText()](#getText--) | Získává nebo nastavuje prostý text pro TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Získává nebo nastavuje prostý text pro TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Vrací objekt formátování pro tento objekt TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Poskytuje snadný přístup k obsaženým hyperodkazům. |
| [getParentShape()](#getParentShape--) | Vrací nadřazený tvar nebo null, pokud nadřazený objekt neimplementuje rozhraní IShape. Pouze pro čtení [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Vrací nadřazenou buňku nebo null, pokud nadřazený objekt neimplementuje rozhraní ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojuje úseky se stejným formátováním ve všech odstavcích. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Zvýrazní všechny shody vzorového textu zadanou barvou. |
| [splitTextByColumns()](#splitTextByColumns--) | Rozdělí textový obsah [ITextFrame](../../com.aspose.slides/itextframe) do pole řetězců, kde každý prvek odpovídá samostatnému sloupci textu v rámci. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Zvýrazní všechny shody vzorového textu zadanou barvou. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zvýrazní všechny shody vzorového textu zadanou barvou. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Zvýrazní všechny shody regulárního výrazu zadanou barvou. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Zvýrazní všechny shody regulárního výrazu zadanou barvou. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Nahradí všechny shody regulárního výrazu zadaným řetězcem. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Vrací seznam všech odstavců v rámečku. Pouze pro čtení [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Vrací:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public abstract String getText()
```

Získává nebo nastavuje prostý text pro TextFrame. Čtení/zápis String.

Hodnota: Text.

**Vrací:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Získává nebo nastavuje prostý text pro TextFrame. Čtení/zápis String.

Hodnota: Text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Vrací objekt formátování pro tento objekt TextFrame. Pouze pro čtení [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Vrací:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Poskytuje snadný přístup k obsaženým hyperodkazům. Pouze pro čtení [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Vrací:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

Vrací nadřazený tvar nebo null, pokud nadřazený objekt neimplementuje rozhraní IShape. Pouze pro čtení [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Tyto tvrzení jsou vždy pravdivé
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

Vrací nadřazenou buňku nebo null, pokud nadřazený objekt neimplementuje rozhraní ICell. Pouze pro čtení [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Tyto tvrzení jsou vždy pravdivé
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Vrací:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Spojuje úseky se stejným formátováním ve všech odstavcích.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Zvýrazní všechny shody vzorového textu zadanou barvou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má zvýraznit. |
| highlightColor | java.lang.Integer | Barva, kterou se má text zvýraznit. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Rozdělí textový obsah [ITextFrame](../../com.aspose.slides/itextframe) do pole řetězců, kde každý prvek odpovídá samostatnému sloupci textu v rámci.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Získá první tvar na snímku a přetypuje jej na ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Rozdělí obsah textového rámce do sloupců
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Vytiskne text každého sloupce na konzoli
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
java.lang.String[] - Pole řetězců, kde každý řetězec představuje textový obsah konkrétního sloupce v [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Pokud textový rámec neobsahuje více sloupců, vrácené pole bude mít jediný prvek obsahující celý text. Prázdné sloupce budou v poli reprezentovány prázdnými řetězci.
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Zvýrazní všechny shody vzorového textu zadanou barvou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má zvýraznit. |
| highlightColor | java.lang.Integer | Barva, kterou se má text zvýraznit. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Možnosti zvýraznění. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Zvýrazní všechny shody vzorového textu zadanou barvou.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // zvýraznění všech slov 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // zvýraznění všech samostatných výskytů 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má zvýraznit. |
| highlightColor | java.lang.Integer | Barva, kterou se má text zvýraznit. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti vyhledávání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Zvýrazní všechny shody regulárního výrazu zadanou barvou.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // zvýraznění všech slov, která mají 5 a více znaků
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regulární výraz java.util.regex.Pattern pro získání řetězců k zvýraznění. |
| highlightColor | java.lang.Integer | Barva, kterou se má text zvýraznit. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Zvýrazní všechny shody regulárního výrazu zadanou barvou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | java.lang.String | Text regulárního výrazu pro získání textu k zvýraznění. |
| highlightColor | java.lang.Integer | Barva, kterou se má text zvýraznit. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Možnosti zvýraznění. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Nahradí všechny výskyty zadaného textu jiným zadaným textem.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Nahradí všechny samostatné výskyty 'the' řetězcem '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| oldText | java.lang.String | Řetězec, který má být nahrazen. |
| newText | java.lang.String | Řetězec, který nahradí všechny výskyty oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti vyhledávání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Nahradí všechny shody regulárního výrazu zadaným řetězcem.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Nahradí všechna slova s 5 a více znaky řetězcem '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regulární výraz java.util.regex.Pattern pro získání řetězců k nahrazení. |
| newText | java.lang.String | Řetězec, který nahradí všechny výskyty řetězců k nahrazení. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |