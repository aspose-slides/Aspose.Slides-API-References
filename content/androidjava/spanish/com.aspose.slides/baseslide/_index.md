---
title: BaseSlide
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Representa datos comunes para todos los tipos de diapositiva.
type: docs
url: /es/com.aspose.slides/baseslide/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Representa datos comunes para todos los tipos de diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getShapes()](#getShapes--) | Devuelve las formas de una diapositiva. |
| [getControls()](#getControls--) | Devuelve la colección de controles ActiveX en una diapositiva. |
| [getName()](#getName--) | Devuelve o establece el nombre de una diapositiva. |
| [setName(String value)](#setName-java.lang.String-) | Devuelve o establece el nombre de una diapositiva. |
| [getSlideId()](#getSlideId--) | Devuelve el ID de una diapositiva. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Determina si dos instancias de IBaseSlide son iguales. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [createThemeEffective()](#createThemeEffective--) | Devuelve un tema efectivo para esta diapositiva. |
| [getCustomData()](#getCustomData--) | Devuelve los datos personalizados de la diapositiva. |
| [getTimeline()](#getTimeline--) | Devuelve el objeto de línea de tiempo de animación. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Devuelve el objeto Transition que contiene información sobre cómo avanza la diapositiva especificada durante una presentación. |
| [getBackground()](#getBackground--) | Devuelve el fondo de la diapositiva. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Proporciona acceso fácil a los hipervínculos contenidos. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Busca la primera aparición de una forma con el texto alternativo especificado. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Devuelve la interfaz IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Devuelve las formas de una diapositiva. Solo lectura [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Devuelve:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Devuelve la colección de controles ActiveX en una diapositiva. Solo lectura [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Devuelve:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Devuelve o establece el nombre de una diapositiva. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Devuelve o establece el nombre de una diapositiva. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Devuelve el ID de una diapositiva. Solo lectura long.

**Devuelve:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Determina si dos instancias de IBaseSlide son iguales. El valor devuelto se calcula en función de la estructura y el contenido estático de la diapositiva. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y demás configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, p. ej., SlideId, ni el contenido dinámico, p. ej., el valor de fecha actual en el marcador de posición de fecha.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | La IBaseSlide para comparar con la IBaseSlide actual. |

**Devuelve:**
boolean -  **true**  si la IBaseSlide especificada es igual a la IBaseSlide actual; de lo contrario,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Une ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Devuelve un tema efectivo para esta diapositiva.

**Devuelve:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Devuelve los datos personalizados de la diapositiva. Solo lectura [ICustomData](../../com.aspose.slides/icustomdata).

**Devuelve:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Devuelve el objeto de línea de tiempo de animación. Solo lectura [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Devuelve:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Devuelve el objeto Transition que contiene información sobre cómo avanza la diapositiva especificada durante una presentación. Solo lectura [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Devuelve:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Devuelve el fondo de la diapositiva. Solo lectura [IBackground](../../com.aspose.slides/ibackground).

**Devuelve:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Proporciona acceso fácil a los hipervínculos contenidos. Solo lectura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Devuelve:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Para la propia diapositiva maestra esta propiedad siempre devuelve false. Lectura/escritura boolean.

**Devuelve:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Para la propia diapositiva maestra esta propiedad siempre devuelve false. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Busca la primera aparición de una forma con el texto alternativo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| altText | java.lang.String | Texto alternativo. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - objeto Shape o null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la interfaz IPresentation. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva base. Solo lectura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)