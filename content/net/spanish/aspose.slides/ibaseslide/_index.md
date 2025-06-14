---
title: IBaseSlide
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa datos comunes para todos los tipos de diapositivas.
type: docs
weight: 5140
url: /es/aspose.slides/ibaseslide/
---

## Interfaz IBaseSlide

Representa datos comunes para todos los tipos de diapositivas.

```csharp
public interface IBaseSlide : IThemeable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIThemeable](../../aspose.slides/ibaseslide/asithemeable) { get; } | Permite obtener la interfaz base IThemeable. Solo lectura [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Background](../../aspose.slides/ibaseslide/background) { get; } | Devuelve el fondo de la diapositiva. Solo lectura [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/ibaseslide/controls) { get; } | Devuelve la colección de controles ActiveX en una diapositiva. Solo lectura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/ibaseslide/customdata) { get; } | Devuelve los datos personalizados de la diapositiva. Solo lectura [`ICustomData`](../icustomdata). |
| [HyperlinkQueries](../../aspose.slides/ibaseslide/hyperlinkqueries) { get; } | Proporciona acceso fácil a los hipervínculos contenidos. Solo lectura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Name](../../aspose.slides/ibaseslide/name) { get; set; } | Devuelve o establece el nombre de una diapositiva. Lectura/escritura String. |
| [Shapes](../../aspose.slides/ibaseslide/shapes) { get; } | Devuelve las formas de una diapositiva. Solo lectura [`IShapeCollection`](../ishapecollection). |
| [ShowMasterShapes](../../aspose.slides/ibaseslide/showmastershapes) { get; set; } | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Para la diapositiva maestra en sí, esta propiedad siempre devuelve `false`. Lectura/escritura Boolean. |
| [SlideId](../../aspose.slides/ibaseslide/slideid) { get; } | Devuelve el ID de una diapositiva. Solo lectura UInt32. |
| [SlideShowTransition](../../aspose.slides/ibaseslide/slideshowtransition) { get; } | Devuelve el objeto TransitionEx que contiene información sobre cómo avanza la diapositiva especificada durante una presentación de diapositivas. Solo lectura [`ISlideShowTransition`](../islideshowtransition). |
| [Timeline](../../aspose.slides/ibaseslide/timeline) { get; } | Devuelve el objeto de línea de tiempo de animación. Solo lectura [`IAnimationTimeLine`](../ianimationtimeline). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../aspose.slides/ibaseslide/equals)(IBaseSlide) | Determina si las dos instancias de IBaseSlide son iguales. El valor de retorno se calcula en función de la estructura y el contenido estático de la diapositiva. Dos diapositivas son iguales si todas las formas, estilos, textos, animación y otros ajustes, etc., son iguales. La comparación no tiene en cuenta los valores de identificador único, p. ej. SlideId y el contenido dinámico, p. ej. el valor de la fecha actual en el marcador de posición de fecha. |
| [FindShapeByAltText](../../aspose.slides/ibaseslide/findshapebyalttext)(string) | Encuentra la primera ocurrencia de una forma con el texto alternativo especificado. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ibaseslide/joinportionswithsameformatting)() | Une porciones con el mismo formato en todos los párrafos en todas las formas aceptables. |

### Ver También

* interfaz [IThemeable](../../aspose.slides.theme/ithemeable)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->