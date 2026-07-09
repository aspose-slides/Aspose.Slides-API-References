---
title: MasterSlide
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa una diapositiva maestra en una presentación.
type: docs
weight: 8030
url: /es/aspose.slides/masterslide/
---
## MasterSlide clase

Representa una diapositiva maestra en una presentación.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Devuelve el fondo de la diapositiva. Solo lectura [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Devuelve el estilo de un texto de cuerpo. Solo lectura [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Devuelve la colección de controles ActiveX en una diapositiva. Solo lectura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Devuelve los datos personalizados de la diapositiva. Solo lectura [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Devuelve una colección de guías de dibujo para la diapositiva maestra. Solo lectura [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Devuelve true si existe al menos una diapositiva que depende de esta diapositiva maestra. Solo lectura Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Devuelve el administrador HeaderFooter de la diapositiva maestra. Solo lectura [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Proporciona acceso fácil a los hipervínculos contenidos. Solo lectura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Devuelve la colección de diapositivas de diseño hijo para esta diapositiva maestra. Solo lectura [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Devuelve o establece el nombre de una diapositiva maestra. Lectura/escritura String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Devuelve el estilo de otro texto. Solo lectura [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Devuelve la interfaz IPresentation. Solo lectura [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Determina si la maestra correspondiente se elimina cuando se eliminan todas las diapositivas que siguen a esa maestra. Nota: Aspose.Slides nunca eliminará ninguna maestra sin usar por sí mismo; para eliminar realmente maestras sin usar llame a [`RemoveUnused`](../masterslidecollection/removeunused) Lectura/escritura Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Devuelve las formas de una diapositiva. Solo lectura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Para la propia diapositiva maestra esta propiedad siempre devuelve `false`. Lectura/escritura Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Devuelve el ID de una diapositiva. Solo lectura UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Devuelve el objeto Transition que contiene información sobre cómo avanza la diapositiva especificada durante una presentación. Solo lectura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Devuelve el administrador de tema. Solo lectura [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Devuelve el objeto de línea de tiempo de animación. Solo lectura [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Devuelve el estilo de un texto de título. Solo lectura [`ITextStyle`](../itextstyle). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Crea una nueva diapositiva maestra basada en la actual, aplicando un tema externo a ella y aplica la diapositiva maestra creada a todas las diapositivas dependientes. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Devuelve un tema efectivo para esta diapositiva. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina si las dos instancias IBaseSlide son iguales. El valor devuelto se calcula en base a la estructura de la diapositiva y al contenido estático. Dos diapositivas son iguales si todas las formas, estilos, textos, animaciones y otras configuraciones, etc., son iguales. La comparación no tiene en cuenta los valores de identificadores únicos, por ejemplo SlideId, ni el contenido dinámico, por ejemplo el valor de fecha actual en el marcador de posición de fecha. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Encuentra la primera aparición de una forma con el texto alternativo especificado. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva maestra. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Une los fragmentos con el mismo formato en todos los párrafos de todas las formas aceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Une los fragmentos con el mismo formato en todos los párrafos de todas las formas aceptables. |

### Ver también

* clase [BaseSlide](../baseslide)
* interfaz [IMasterSlide](../imasterslide)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->