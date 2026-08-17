---
title: IMathParagraph
second_title: Référence de l'API Aspose.Slides pour Java
description: Paragraphe mathématique qui est un conteneur pour des blocs mathématiques IMathBlock
type: docs
url: /fr/com.aspose.slides/imathparagraph/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IMathBlockCollection](../../com.aspose.slides/imathblockcollection)
```
public interface IMathParagraph extends IMathBlockCollection
```

Paragraphe mathématique qui est un conteneur pour des blocs mathématiques (IMathBlock)

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getJustification()](#getJustification--) | Justification du paragraphe Valeur par défaut : CenteredAsGroup |
| [setJustification(int value)](#setJustification-int-) | Justification du paragraphe Valeur par défaut : CenteredAsGroup |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Enregistre le contenu de ce [IMathParagraph](../../com.aspose.slides/imathparagraph) au format MathML |
| [toLatex()](#toLatex--) | Obtient l’équation mathématique au format LaTeX |
### getJustification() {#getJustification--}
```
public abstract int getJustification()
```


Justification du paragraphe Valeur par défaut : CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Retourne :**
int
### setJustification(int value) {#setJustification-int-}
```
public abstract void setJustification(int value)
```


Justification du paragraphe Valeur par défaut : CenteredAsGroup

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.setJustification(MathJustification.LeftJustified);
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Enregistre le contenu de ce [IMathParagraph](../../com.aspose.slides/imathparagraph) au format MathML

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux cible |

### toLatex() {#toLatex--}
```
public abstract String toLatex()
```


Obtient l’équation mathématique au format LaTeX

--------------------

> ```
> Example:
>  
>  IAutoShape shape = slide.getShapes().addMathShape(x, y, width, height);
>  IMathParagraph mathParagraph = ((MathPortion)shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>  mathParagraph.add(new MathematicalText("a").join("+").join(new MathematicalText("b").join("=").join(new MathematicalText("c"))));
>  String mathLatex = mathParagraph.toLatex();
> ```

**Retourne :**
java.lang.String