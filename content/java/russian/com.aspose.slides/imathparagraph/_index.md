---
title: IMathParagraph
second_title: Aspose.Slides для Java: справочник API
description: Математический абзац, являющийся контейнером для математических блоков IMathBlock
type: docs
url: /ru/com.aspose.slides/imathparagraph/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Математический абзац, который является контейнером для математических блоков (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getJustification()](#getJustification--) | Paragraph Justification Default value: CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Paragraph Justification Default value: CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Сохраняет содержимое этого [IMathParagraph](../../com.aspose.slides/imathparagraph) в формате MathML |
| [toLatex()](#toLatex--) | Получает математическое уравнение в формате LaTeX |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Paragraph Justification Default value: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Возвращаемое значение:**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Paragraph Justification Default value: CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Сохраняет содержимое этого [IMathParagraph](../../com.aspose.slides/imathparagraph) в формате MathML

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


Получает математическое уравнение в формате LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Возвращаемое значение:**
java.lang.String