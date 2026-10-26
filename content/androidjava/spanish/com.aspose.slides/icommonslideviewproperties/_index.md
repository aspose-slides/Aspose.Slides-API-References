---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Representa las propiedades comunes de la vista de diapositiva.
type: docs
url: /es/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Representa las propiedades comunes de la vista de diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getScale()](#getScale--) | Especifica la proporción de escalado de la vista en porcentajes. |
| [setScale(int value)](#setScale-int-) | Especifica la proporción de escalado de la vista en porcentajes. |
| [getVariableScale()](#getVariableScale--) | Especifica que el contenido de la vista debe escalarse automáticamente para ajustarse mejor al tamaño actual de la ventana. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Especifica que el contenido de la vista debe escalarse automáticamente para ajustarse mejor al tamaño actual de la ventana. |
| [getDrawingGuides()](#getDrawingGuides--) | Devuelve la colección de guías de dibujo. |
### getScale() {#getScale--}
```
public abstract int getScale()
```

Especifica la proporción de escalado de la vista en porcentajes. Lectura/escritura int.

**Devuelve:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```

Especifica la proporción de escalado de la vista en porcentajes. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```

Especifica que el contenido de la vista debe escalarse automáticamente para ajustarse mejor al tamaño actual de la ventana. Lectura/escritura boolean.

**Devuelve:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```

Especifica que el contenido de la vista debe escalarse automáticamente para ajustarse mejor al tamaño actual de la ventana. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Devuelve la colección de guías de dibujo. Solo lectura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Añadiendo la nueva guía de dibujo vertical a la derecha del centro de la diapositiva
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>      // Añadiendo la nueva guía de dibujo horizontal debajo del centro de la diapositiva
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)