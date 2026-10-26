---
title: IMathBorderBoxFactory
second_title: Aspose.Slides per Android via Riferimento API Java
description: Consente di creare una casella di contorno matematico
type: docs
url: /it/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Consente di creare una casella di contorno matematico

--------------------

Per compatibilità COM
## Metodi

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Crea una casella di contorno matematico applicandola all'elemento |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Crea una casella di contorno matematico applicandola all'elemento |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```


Crea una casella di contorno matematico applicandola all'elemento

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare la casella di contorno |

**Restituisce:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuovo elemento di casella di contorno
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Crea una casella di contorno matematico applicandola all'elemento

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare la casella di contorno |
| hideTop | boolean | Nascondi bordo superiore |
| hideBottom | boolean | Nascondi bordo inferiore |
| hideLeft | boolean | Nascondi bordo sinistro |
| hideRight | boolean | Nascondi bordo destro |
| strikethroughHorizontal | boolean | Barra orizzontale attraversata della casella di contorno |
| strikethroughVertical | boolean | Barra verticale attraversata della casella di contorno |
| strikethroughBottomLeftToTopRight | boolean | Barra attraversata da in basso a sinistra a in alto a destra della casella di contorno |
| strikethroughTopLeftToBottomRight | boolean | Barra attraversata da in alto a sinistra a in basso a destra della casella di contorno |

**Restituisce:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuovo elemento di casella di contorno