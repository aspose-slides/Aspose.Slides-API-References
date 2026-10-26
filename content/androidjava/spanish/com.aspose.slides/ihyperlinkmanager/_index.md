---
title: IHyperlinkManager
second_title: Aspose.Slides for Android via Java API Reference
description: Proporciona la gestión de hipervínculos al agregar y eliminar.
type: docs
url: /es/com.aspose.slides/ihyperlinkmanager/
---```
public interface IHyperlinkManager
```

Proporciona la gestión de hipervínculos (agregar, eliminar).
## Métodos

| Method | Description |
| --- | --- |
| [setExternalHyperlinkClick(String url)](#setExternalHyperlinkClick-java.lang.String-) | Establece un hipervínculo externo al hacer clic. |
| [setInternalHyperlinkClick(ISlide targetSlide)](#setInternalHyperlinkClick-com.aspose.slides.ISlide-) | Establece un hipervínculo interno al hacer clic. |
| [removeHyperlinkClick()](#removeHyperlinkClick--) | Elimina el hipervínculo al hacer clic. |
| [setExternalHyperlinkMouseOver(String url)](#setExternalHyperlinkMouseOver-java.lang.String-) | Establece un hipervínculo externo al pasar el ratón. |
| [setInternalHyperlinkMouseOver(ISlide targetSlide)](#setInternalHyperlinkMouseOver-com.aspose.slides.ISlide-) | Establece un hipervínculo interno al pasar el ratón. |
| [removeHyperlinkMouseOver()](#removeHyperlinkMouseOver--) | Elimina el hipervínculo al pasar el ratón. |
| [setMacroHyperlinkClick(String macroName)](#setMacroHyperlinkClick-java.lang.String-) | Establece un hipervínculo macro al hacer clic. |
### setExternalHyperlinkClick(String url) {#setExternalHyperlinkClick-java.lang.String-}
```
public abstract IHyperlink setExternalHyperlinkClick(String url)
```

Establece un hipervínculo externo al hacer clic.

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| url | java.lang.String | URL del hipervínculo. |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - objeto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)
### setInternalHyperlinkClick(ISlide targetSlide) {#setInternalHyperlinkClick-com.aspose.slides.ISlide-}
```
public abstract IHyperlink setInternalHyperlinkClick(ISlide targetSlide)
```

Establece un hipervínculo interno al hacer clic.

**Parámetros:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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

Establece un hipervínculo macro al hacer clic.

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
| Parameter | Type | Description |
| --- | --- | --- |
| macroName | java.lang.String | Nombre de la macro |

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink) - objeto Hyperlink [IHyperlink](../../com.aspose.slides/ihyperlink)