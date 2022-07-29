---
title: MasterSlide
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una diapositiva patrón en una presentación.
type: docs
weight: 7320
url: /es/net/aspose.slides/masterslide/
---
## MasterSlide class

Representa una diapositiva patrón en una presentación.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Devuelve el fondo de la diapositiva. Solo lectura[`IBackground`](../ibackground) . |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Devuelve el estilo de un cuerpo de texto. Solo lectura[`ITextStyle`](../itextstyle) . |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Devuelve la colección de controles ActiveX en una diapositiva. Solo lectura[`IControlCollection`](../icontrolcollection) . |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Devuelve los datos personalizados de la diapositiva. Solo lectura[`ICustomData`](../icustomdata) . |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Devuelve verdadero si existe al menos una diapositiva que depende de esta diapositiva maestra. Solo lecturaBoolean . |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Devuelve el administrador de encabezado y pie de página de la diapositiva maestra. Solo lectura[`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Proporciona fácil acceso a hipervínculos contenidos. Solo lectura[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Devuelve la colección de diapositivas de diseño secundarias para esta diapositiva maestra. Solo lectura[`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection) . |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Devuelve o establece el nombre de una diapositiva patrón. Lectura/escrituraString . |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Devuelve el estilo de otro texto. Solo lectura[`ITextStyle`](../itextstyle) . |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Devuelve la interfaz IPPresentation. Solo lectura[`IPresentation`](../ipresentation) . |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Determina si el patrón correspondiente se elimina cuando se eliminan todas las diapositivas que siguen a ese patrón.[`RemoveUnused`](../masterslidecollection/removeunused) Lectura/escrituraBoolean . |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Devuelve las formas de una diapositiva. Solo lectura[`IShapeCollection`](../ishapecollection) . |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Especifica si las formas de la diapositiva maestra deben mostrarse en las diapositivas o no. Para la diapositiva maestra en sí, esta propiedad siempre devuelve`falso` . Lectura/escrituraBoolean . |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Devuelve el ID de una diapositiva. Solo lecturaUInt32 . |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Devuelve el objeto Transición que contiene información sobre cómo avanza la diapositiva especificada durante una presentación de diapositivas. Solo lectura[`ISlideShowTransition`](../islideshowtransition) . |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Devuelve el administrador de temas. Solo lectura[`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager) . |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Devuelve el objeto de la línea de tiempo de la animación. Solo lectura[`IAnimationTimeLine`](../ianimationtimeline) . |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Devuelve el estilo de un texto de título. Solo lectura[`ITextStyle`](../itextstyle) . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Crea una nueva diapositiva maestra basada en la actual, aplicándole un tema externo y aplica la diapositiva maestra creada a todas las diapositivas dependientes. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Devuelve un tema efectivo para esta diapositiva. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina si las dos instancias de IBaseSlide son iguales. El valor devuelto se calcula según la estructura de la diapositiva y el contenido estático. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones. etc son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, por ejemplo, SlideId y contenido dinámico, por ejemplo, el valor de fecha actual en Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Encuentra la primera aparición de una forma con el texto alternativo especificado. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva maestra. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Une ejecuciones con el mismo formato en todos los párrafos todas las formas aceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Une las ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables. |

### Ver también

* class [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
