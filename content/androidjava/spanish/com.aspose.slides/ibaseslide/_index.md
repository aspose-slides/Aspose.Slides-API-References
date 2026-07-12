---
title: IBaseSlide
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa datos comunes para todos los tipos de diapositivas.
type: docs
url: /es/com.aspose.slides/ibaseslide/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Representa datos comunes para todos los tipos de diapositivas.
## Métodos

| Método | Descripción |
| --- | --- |
| [getShapes()](#getShapes--) | Devuelve las formas de una diapositiva. |
| [getControls()](#getControls--) | Devuelve la colección de controles ActiveX en una diapositiva. |
| [getName()](#getName--) | Devuelve o establece el nombre de una diapositiva. |
| [setName(String value)](#setName-java.lang.String-) | Devuelve o establece el nombre de una diapositiva. |
| [getSlideId()](#getSlideId--) | Devuelve el ID de una diapositiva. |
| [getCustomData()](#getCustomData--) | Devuelve los datos personalizados de la diapositiva. |
| [getTimeline()](#getTimeline--) | Devuelve el objeto de línea de tiempo de animación. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Devuelve el objeto TransitionEx que contiene información sobre cómo avanza la diapositiva especificada durante una presentación. |
| [getBackground()](#getBackground--) | Devuelve el fondo de la diapositiva. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Proporciona acceso fácil a los hipervínculos contenidos. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Encuentra la primera ocurrencia de una forma con el texto alternativo especificado. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une fragmentos con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Determina si las dos instancias de IBaseSlide son iguales. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Devuelve las formas de una diapositiva. Solo lectura [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Devuelve:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Devuelve la colección de controles ActiveX en una diapositiva. Solo lectura [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Devuelve:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

Devuelve o establece el nombre de una diapositiva. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Devuelve o establece el nombre de una diapositiva. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Devuelve el ID de una diapositiva. Solo lectura long.

**Devuelve:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Devuelve los datos personalizados de la diapositiva. Solo lectura [ICustomData](../../com.aspose.slides/icustomdata).

**Devuelve:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Devuelve el objeto de línea de tiempo de animación. Solo lectura [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Devuelve:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Devuelve el objeto TransitionEx que contiene información sobre cómo avanza la diapositiva especificada durante una presentación. Solo lectura [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Devuelve:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Devuelve el fondo de la diapositiva. Solo lectura [IBackground](../../com.aspose.slides/ibackground).

**Devuelve:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
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
public abstract IShape findShapeByAltText(String altText)
```

Encuentra la primera ocurrencia de una forma con el texto alternativo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| altText | java.lang.String | Texto alternativo. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - objeto ShapeEx o null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Une fragmentos con el mismo formato en todos los párrafos de todas las formas aceptables.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Determina si las dos instancias de IBaseSlide son iguales. El valor devuelto se calcula basándose en la estructura de la diapositiva y el contenido estático. Dos diapositivas son iguales si todas sus formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, por ejemplo SlideId, y el contenido dinámico, por ejemplo el valor de fecha actual en el marcador de posición de fecha.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | El IBaseSlide a comparar con el IBaseSlide actual. |

**Devuelve:**
boolean - **true** si el IBaseSlide especificado es igual al IBaseSlide actual; de lo contrario, **false**.