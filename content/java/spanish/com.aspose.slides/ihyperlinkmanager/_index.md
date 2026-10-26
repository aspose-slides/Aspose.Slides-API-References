---
title: IHyperlinkManager
second_title: Aspose.Slides for Java API Reference
description: Proporciona la gestión de hipervínculos (agregar, eliminar).
type: docs
url: /es/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Proporciona la gestión de hipérlink (agregar, eliminar).

## Métodos

| Método | Descripción |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Set external hyperlink on click. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Sets internal hyperlink on click. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Removes hyperlink on click. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Sets external hyperlink mouse over. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Sets internal hyperlink mouse over. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Removes hyperlink mouse over. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Set Macro hyperlink on a click. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Establece un hipervínculo externo al hacer clic.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del hipervínculo. |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Objeto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Establece un hipervínculo interno al hacer clic.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva de destino. |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkClick() {#removeHyperlinkClick--}
```
public abstract void removeHyperlinkClick()
```

Elimina el hipervínculo al hacer clic.

### setExternalHyperlinkMouseOver(String url) {#setExternalHyperlinkMouseOver-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkMouseOver(String url)
```

Establece un hipervínculo externo al pasar el ratón.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| url | java.lang.String | URL del hipervínculo. |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### setInternalHyperlinkMouseOver(ISlide targetSlide) {#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkMouseOver(ISlide targetSlide)
```

Establece un hipervínculo interno al pasar el ratón.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetSlide | [ISlide](../../com.aspose.slides/islide) | Diapositiva de destino. |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - Hyperlink.
### removeHyperlinkMouseOver() {#removeHyperlinkMouseOver--}
```
public abstract void removeHyperlinkMouseOver()
```

Elimina el hipervínculo al pasar el ratón.

### setMacroHyperlinkClick(String macroName) {#setMacroHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setMacroHyperlinkClick(String macroName)
```

Establece un hipervínculo Macro al hacer clic.

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
[IHyperlink](../../com.aspose.slides/ihyperlink) - Objeto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)