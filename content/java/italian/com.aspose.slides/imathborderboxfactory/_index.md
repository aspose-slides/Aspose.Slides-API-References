---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Consente di creare un riquadro di bordo matematico
type: docs
url: /it/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Consente di creare un riquadro di bordo matematico

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Crea un riquadro di bordo matematico applicandolo all'elemento |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Crea un riquadro di bordo matematico applicandolo all'elemento |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```


Crea un riquadro di bordo matematico applicandolo all'elemento

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare il riquadro di bordo |

**Restituisce:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuovo elemento riquadro di bordo
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Crea un riquadro di bordo matematico applicandolo all'elemento

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare il riquadro di bordo |
| hideTop | boolean | Nascondi bordo superiore |
| hideBottom | boolean | Nascondi bordo inferiore |
| hideLeft | boolean | Nascondi bordo sinistro |
| hideRight | boolean | Nascondi bordo destro |
| strikethroughHorizontal | boolean | Riquadro di bordo barrato orizzontalmente |
| strikethroughVertical | boolean | Riquadro di bordo barrato verticalmente |
| strikethroughBottomLeftToTopRight | boolean | Riquadro di bordo barrato da basso-sinistra a alto-destra |
| strikethroughTopLeftToBottomRight | boolean | Riquadro di bordo barrato da alto-sinistra a basso-destra |

**Restituisce:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuovo elemento riquadro di bordo