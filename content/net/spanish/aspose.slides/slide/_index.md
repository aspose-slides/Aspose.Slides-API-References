---
title: Slide
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una diapositiva en una presentación.
type: docs
weight: 9180
url: /es/aspose.slides/slide/
---
## Slide class

Representa una diapositiva en una presentación.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Devuelve el fondo de la diapositiva. Solo lectura[`IBackground`](../ibackground) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Devuelve la colección de controles ActiveX en una diapositiva. Solo lectura[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Devuelve los datos personalizados de la diapositiva. Solo lectura[`ICustomData`](../icustomdata) . |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Devuelve el administrador de encabezado y pie de página de la diapositiva. Solo lectura[`ISlideHeaderFooterManager`](../islideheaderfootermanager) . |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Determina si la diapositiva especificada se oculta durante una presentación de diapositivas. Lectura/escrituraBoolean . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Proporciona fácil acceso a hipervínculos contenidos. Solo lectura[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Devuelve o establece la diapositiva de diseño para la diapositiva actual. Lectura/escritura[`ILayoutSlide`](../ilayoutslide) . |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Devuelve o establece el nombre de una diapositiva. Lectura/escrituraString . |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Permitir acceder a la diapositiva de notas, agregarla y eliminarla. Solo lectura[`INotesSlideManager`](../inotesslidemanager) . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Devuelve la interfaz IPPresentation. Solo lectura[`IPresentation`](../ipresentation) . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Devuelve las formas de una diapositiva. Solo lectura[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Especifica si las formas de la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escrituraBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Devuelve el ID de una diapositiva. Solo lecturaUInt32 . |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Devuelve un número de diapositiva. Índice de diapositiva en[`Slides`](../presentation/slides) la colección siempre es igual a SlideNumber - Presentation.FirstSlideNumber. Lectura/escrituraInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Devuelve el objeto Transición que contiene información sobre cómo avanza la diapositiva especificada durante una presentación de diapositivas. Solo lectura[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Devuelve el administrador de temas principal. Solo lectura[`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Devuelve el objeto de la línea de tiempo de la animación. Solo lectura[`IAnimationTimeLine`](../ianimationtimeline) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Devuelve un tema efectivo para esta diapositiva. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina si las dos instancias de IBaseSlide son iguales. El valor devuelto se calcula según la estructura de la diapositiva y el contenido estático. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones. etc son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, por ejemplo, SlideId y contenido dinámico, por ejemplo, el valor de fecha actual en Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Encuentra la primera aparición de una forma con el texto alternativo especificado. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Devuelve todos los comentarios de diapositiva agregados por un autor específico. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail)() | Devuelve un objeto Imagen en miniatura (20% del tamaño real). |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_4)(IRenderingOptions) | Devuelve un objeto de mapa de bits en miniatura. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_7)(ITiffOptions) | Devuelve un objeto de mapa de bits tiff en miniatura con los parámetros especificados. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_9)(Size) | Devuelve un objeto de mapa de bits en miniatura con el tamaño especificado. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_8)(float, float) | Devuelve un objeto de mapa de bits en miniatura con escala personalizada. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_6)(IRenderingOptions, Size) | Devuelve un objeto de mapa de bits en miniatura con el tamaño especificado. |
| [GetThumbnail](../../aspose.slides/slide/getthumbnail#getthumbnail_5)(IRenderingOptions, float, float) | Devuelve un objeto de mapa de bits en miniatura con escala personalizada. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Une las ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Une las ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables. |
| [Remove](../../aspose.slides/slide/remove)() | Elimina la diapositiva de la presentación. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_3)(IRenderingOptions, Graphics) | Renderiza cierta diapositiva a un objeto Graphics. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_5)(IRenderingOptions, Graphics, Size) | Renderiza cierta diapositiva a un objeto Graphics usando el tamaño especificado. |
| [RenderToGraphics](../../aspose.slides/slide/rendertographics#rendertographics_4)(IRenderingOptions, Graphics, float, float) | Renderiza cierta diapositiva a un objeto Graphics con escalado personalizado. |
| [Reset](../../aspose.slides/slide/reset)() | Restablece la posición, el tamaño y el formato de cada forma que tiene un prototipo en LayoutSlide. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Guarda el contenido de la diapositiva como archivo SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Guarda el contenido de la diapositiva como archivo SVG. |

### Ver también

* class [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
