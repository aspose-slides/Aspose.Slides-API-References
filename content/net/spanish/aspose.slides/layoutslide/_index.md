---
title: LayoutSlide
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una diapositiva de diseño.
type: docs
weight: 7400
url: /es/aspose.slides/layoutslide/
---

## Clase LayoutSlide

Representa una diapositiva de diseño.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Devuelve el fondo de la diapositiva. Solo lectura [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Devuelve la colección de controles ActiveX en una diapositiva. Solo lectura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Devuelve los datos personalizados de la diapositiva. Solo lectura [`ICustomData`](../icustomdata). |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Devuelve verdadero si existe al menos una diapositiva que depende de esta diapositiva de diseño. Solo lectura Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Devuelve el administrador de encabezado y pie de página de la diapositiva de diseño. Solo lectura [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Proporciona fácil acceso a los hipervínculos contenidos. Solo lectura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Devuelve el tipo de diseño de esta diapositiva de diseño. Solo lectura [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Devuelve o establece la diapositiva maestra para un diseño. Lectura/escritura [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Devuelve o establece el nombre de una diapositiva. Lectura/escritura String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Devuelve el administrador de marcadores de posición de la diapositiva de diseño. Solo lectura [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Devuelve la interfaz IPresentation. Solo lectura [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Devuelve las formas de una diapositiva. Solo lectura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escritura Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Devuelve el ID de una diapositiva. Solo lectura UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Devuelve el objeto de transición que contiene información sobre cómo avanza la diapositiva especificada durante una presentación. Solo lectura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Devuelve el administrador de tema de anulación. Solo lectura [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Devuelve el objeto de línea de tiempo de animación. Solo lectura [`IAnimationTimeLine`](../ianimationtimeline). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Devuelve un tema efectivo para esta diapositiva. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina si las dos instancias de IBaseSlide son iguales. El valor devuelto se calcula en función de la estructura de la diapositiva y el contenido estático. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc. son iguales. La comparación no toma en cuenta los valores de identificador único, p. ej. SlideId y contenido dinámico, p. ej. el valor de la fecha actual en el marcador de posición de fecha. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Encuentra la primera ocurrencia de una forma con el texto alternativo especificado. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Devuelve un array con todas las diapositivas que dependen de esta diapositiva de diseño. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Une partes con el mismo formato en todos los párrafos de todas las formas aceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Une partes con el mismo formato en todos los párrafos de todas las formas aceptables. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Elimina el diseño de la presentación. |

### Véase También

* clase [BaseSlide](../baseslide)
* interfaz [ILayoutSlide](../ilayoutslide)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblaje [Aspose.Slides](../../)