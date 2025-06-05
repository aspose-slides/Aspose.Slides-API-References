---
title: NotesSlide
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una diapositiva de notas en una presentación.
type: docs
weight: 8870
url: /es/aspose.slides/notesslide/
---

## Clase NotesSlide

Representa una diapositiva de notas en una presentación.

```csharp
public class NotesSlide : BaseSlide, INotesSlide
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Devuelve el fondo de la diapositiva. Solo lectura [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Devuelve la colección de controles ActiveX en una diapositiva. Solo lectura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Devuelve los datos personalizados de la diapositiva. Solo lectura [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/notesslide/headerfootermanager) { get; } | Devuelve el administrador de encabezados y pies de página de la diapositiva de notas. Solo lectura [`INotesSlideHeaderFooterManager`](../inotesslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Proporciona acceso fácil a los hipervínculos contenidos. Solo lectura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Devuelve o establece el nombre de una diapositiva. Lectura/escritura String. |
| [NotesTextFrame](../../aspose.slides/notesslide/notestextframe) { get; } | Devuelve un TextFrame con el texto de las notas si hay uno. Solo lectura [`ITextFrame`](../itextframe). |
| [ParentSlide](../../aspose.slides/notesslide/parentslide) { get; } | Devuelve la diapositiva principal. Solo lectura [`ISlide`](../islide). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Devuelve la interfaz IPresentation. Solo lectura [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Devuelve las formas de una diapositiva. Solo lectura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/notesslide/showmastershapes) { get; set; } | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escritura Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Devuelve el ID de una diapositiva. Solo lectura UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Devuelve el objeto Transition que contiene información sobre cómo avanza la diapositiva especificada durante una presentación de diapositivas. Solo lectura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/notesslide/thememanager) { get; } | Devuelve el administrador de temas de anulación. Solo lectura [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Devuelve el objeto de línea de tiempo de animación. Solo lectura [`IAnimationTimeLine`](../ianimationtimeline). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Devuelve un tema efectivo para esta diapositiva. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina si las dos instancias de IBaseSlide son iguales. El valor devuelto se calcula en función de la estructura de la diapositiva y el contenido estático. Dos diapositivas son iguales si todas las formas, estilos, textos, animación y otras configuraciones, etc. son iguales. La comparación no tiene en cuenta los valores de identificador único, p. ej. SlideId y contenido dinámico, p. ej. valor de fecha actual en el marcador de posición de fecha. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Encuentra la primera ocurrencia de una forma con el texto alternativo especificado. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Une las ejecuciones con el mismo formato en todos los párrafos de todas las formas aceptables. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Une las ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables. |

### Ver también

* clase [BaseSlide](../baseslide)
* interfaz [INotesSlide](../inotesslide)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)