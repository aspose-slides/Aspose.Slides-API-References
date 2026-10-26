---
title: HyperlinkManager
second_title: Referencia de API de Aspose.Slides para Java
description: Proporciona la gestión de hipervínculos, agregando y eliminando.
type: docs
url: /es/com.aspose.slides/hyperlinkmanager/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager), com.aspose.slides.IDOMObject
```
public final class HyperlinkManager implements IHyperlinkManager, IDOMObject
```

Proporciona gestión de hipervínculos (agregar, eliminar).
## Métodos

| Método | Descripción |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Establece un hipervínculo externo al hacer clic. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Establece un hipervínculo interno al hacer clic. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Elimina el hipervínculo al hacer clic. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Establece un hipervínculo externo al pasar el ratón. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Establece un hipervínculo interno al pasar el ratón. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Elimina el hipervínculo al pasar el ratón. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Establece un hipervínculo de macro al hacer clic. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkClick(String url)
```

Establece un hipervínculo externo al hacer clic.

--------------------

> ```
> The following sample code shows how to add Text Box with Hyperlink.
>  
>  // Instancia una clase Presentation que representa un PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Obtiene la primera diapositiva de la presentación
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Añade un objeto AutoShape con el tipo establecido como Rectángulo
>      IShape pptxShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 150, 150, 150, 50);
>      // Convierte la forma a AutoShape
>      IAutoShape pptxAutoShape = (IAutoShape) pptxShape;
>      // Accede a la propiedad ITextFrame asociada con el AutoShape
>      pptxAutoShape.addTextFrame("");
>      ITextFrame textFrame = pptxAutoShape.getTextFrame();
>      IPortion portion = textFrame.getParagraphs().get_Item(0).getPortions().get_Item(0);
>      // Añade texto al marco
>      portion.setText("Aspose.Slides");
>      // Establece el hipervínculo para el texto de la porción
>      IHyperlinkManager hypMan = portion.getPortionFormat().getHyperlinkManager();
>      hypMan.setExternalHyperlinkClick("http://www.aspose.com");
>      // Guarda la presentación PPTX
>      pres.save("hLinkPPTX_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del hipervínculo. |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Establece un hipervínculo interno al hacer clic.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva de destino. |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hipervínculo.

### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public final void removeHyperlinkClick()
```

Elimina el hipervínculo al hacer clic.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public final IHyperlink setExternalHyperlinkMouseOver(String url)
```

Establece un hipervínculo externo al pasar el ratón.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del hipervínculo. |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hipervínculo.

### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public final IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Establece un hipervínculo interno al pasar el ratón.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva de destino. |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hipervínculo.

### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public final void removeHyperlinkMouseOver()
```

Elimina el hipervínculo al pasar el ratón.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public final IHyperlink setMacroHyperlinkClick(String macroName)
```

Establece un hipervínculo de macro al hacer clic.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.BlankButton, 20, 20, 80, 30);
>      shape.getHyperlinkManager().setMacroHyperlinkClick("MacroName");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| macroName | java.lang.String | Nombre de la macro |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - objeto Hipervínculo [IHyperlink](../../com.aspose.slides/ihyperlink)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. IDOMObject de solo lectura.

**Devuelve:**
com.aspose.slides.IDOMObject