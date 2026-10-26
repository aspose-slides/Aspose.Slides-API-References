---
title: CommonSlideViewProperties
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa propiedades comunes de la vista de diapositiva.
type: docs
url: /es/com.aspose.slides/commonslideviewproperties/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Representa propiedades comunes de la vista de diapositiva.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Instancia un objeto Presentation que representa un archivo de presentación
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Configuración de las propiedades de vista de la presentación
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Valor de zoom en porcentajes para la vista de diapositiva
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Valor de zoom en porcentajes para la vista de notas
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descripción |
| --- | --- |
| [getScale()](#getScale--) | Especifica la proporción de escala de la vista en porcentajes. |
| [setScale(int value)](#setScale-int-) | Especifica la proporción de escala de la vista en porcentajes. |
| [getVariableScale()](#getVariableScale--) | Especifica que el contenido de la vista debe escalarse automáticamente para ajustarse mejor al tamaño actual de la ventana. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Especifica que el contenido de la vista debe escalarse automáticamente para ajustarse mejor al tamaño actual de la ventana. |
| [getDrawingGuides()](#getDrawingGuides--) | Devuelve la colección de guías de dibujo. |
### getScale() {#getScale--}
```
public final int getScale()
```

Especifica la proporción de escala de la vista en porcentajes. Lectura/escritura int.

**Devuelve:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Especifica la proporción de escala de la vista en porcentajes. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Especifica que el contenido de la vista debe escalarse automáticamente para ajustarse mejor al tamaño actual de la ventana. Lectura/escritura boolean.

**Devuelve:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Especifica que el contenido de la vista debe escalarse automáticamente para ajustarse mejor al tamaño actual de la ventana. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
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
>      // Agregando la nueva guía de dibujo vertical a la derecha del centro de la diapositiva
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Agregando la nueva guía de dibujo horizontal debajo del centro de la diapositiva
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)