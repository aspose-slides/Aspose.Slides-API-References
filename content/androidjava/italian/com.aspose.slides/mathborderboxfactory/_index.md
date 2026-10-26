---
title: MathBorderBoxFactory
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Consente di creare una casella di bordo matematica
type: docs
url: /it/com.aspose.slides/mathborderboxfactory/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Consente di creare una casella di bordo matematica

--------------------

Per compatibilità COM
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Creare una casella di bordo matematica applicandola all'elemento |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Creare una casella di bordo matematica applicandola all'elemento |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

Crea una casella di bordo matematica applicandola all'elemento

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare la casella di bordo |

**Restituisce:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuovo elemento casella di bordo
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Crea una casella di bordo matematica applicandola all'elemento

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare la casella di bordo |
| hideTop | boolean | Nascondi bordo superiore |
| hideBottom | boolean | Nascondi bordo inferiore |
| hideLeft | boolean | Nascondi bordo sinistro |
| hideRight | boolean | Nascondi bordo destro |
| strikethroughHorizontal | boolean | Barra di attraversamento orizzontale della casella di bordo |
| strikethroughVertical | boolean | Barra di attraversamento verticale della casella di bordo |
| strikethroughBottomLeftToTopRight | boolean | Barra di attraversamento dalla parte inferiore sinistra alla parte superiore destra della casella di bordo |
| strikethroughTopLeftToBottomRight | boolean | Barra di attraversamento dalla parte superiore sinistra alla parte inferiore destra della casella di bordo |

**Restituisce:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuovo elemento casella di bordo