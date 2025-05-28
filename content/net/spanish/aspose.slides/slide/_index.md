---
title: Diapositiva
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una diapositiva en una presentación.
type: docs
weight: 9650
url: /es/aspose.slides/slide/
---

## Clase Slide

Representa una diapositiva en una presentación.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Devuelve el fondo de la diapositiva. Solo lectura [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Devuelve la colección de controles ActiveX en una diapositiva. Solo lectura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Devuelve los datos personalizados de la diapositiva. Solo lectura [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Devuelve el administrador de encabezado y pie de página de la diapositiva. Solo lectura [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Determina si la diapositiva especificada está oculta durante una presentación. Lectura/escritura Booleano. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Proporciona acceso fácil a los hipervínculos contenidos. Solo lectura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Devuelve o establece la diapositiva de diseño para la diapositiva actual. Lectura/escritura [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Devuelve o establece el nombre de una diapositiva. Lectura/escritura String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Permite acceder a la diapositiva de notas, agregarla y quitarla. Solo lectura [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Devuelve la interfaz IPresentation. Solo lectura [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Devuelve las formas de una diapositiva. Solo lectura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escritura Booleano. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Devuelve el ID de una diapositiva. Solo lectura UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Devuelve un número de diapositiva. El índice de la diapositiva en la colección [`Slides`](../presentation/slides) siempre es igual a SlideNumber - Presentation.FirstSlideNumber. Lectura/escritura Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Devuelve el objeto Transition que contiene información sobre cómo avanza la diapositiva especificada durante una presentación. Solo lectura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Devuelve el administrador de temas de anulación. Solo lectura [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Devuelve el objeto de línea de tiempo de animación. Solo lectura [`IAnimationTimeLine`](../ianimationtimeline). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Devuelve un tema efectivo para esta diapositiva. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina si las dos instancias de IBaseSlide son iguales. El valor de retorno se calcula en función de la estructura y contenido estático de la diapositiva. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otros ajustes, etc. son iguales. La comparación no tiene en cuenta los valores de identificador únicos, por ejemplo, SlideId y contenido dinámico, por ejemplo, el valor de la fecha actual en el marcador de posición de Fecha. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Encuentra la primera ocurrencia de una forma con el texto alternativo especificado. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Devuelve un objeto de imagen en miniatura (20% del tamaño real). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Devuelve un objeto de imagen en miniatura. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Devuelve un objeto de imagen tiff en miniatura con los parámetros especificados. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Devuelve un objeto de imagen en miniatura con el tamaño especificado. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Devuelve un objeto de imagen en miniatura con escalado personalizado. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Devuelve un objeto de imagen en miniatura con el tamaño especificado. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Devuelve un objeto de imagen en miniatura con escalado personalizado. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Devuelve todos los comentarios de la diapositiva añadidos por un autor específico. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Une ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Une ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables. |
| [Remove](../../aspose.slides/slide/remove)() | Elimina la diapositiva de la presentación. |
| [Reset](../../aspose.slides/slide/reset)() | Restablece la posición, tamaño y formato de cada forma que tiene un prototipo en LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Guarda el contenido de la diapositiva como un archivo EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Guarda el contenido de la diapositiva como un archivo SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Guarda el contenido de la diapositiva como un archivo SVG. |

### Ver También

* clase [BaseSlide](../baseslide)
* interfaz [ISlide](../islide)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->