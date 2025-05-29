---
title: Aspose.Slides.Effects
second_title: Referencia de API de Aspose.Slides para .NET
description: Contiene clases para trabajar con varios efectos en presentaciones de Microsoft PowerPoint.
type: docs
weight: 50
url: /es/aspose.slides.effects/
---

Contiene clases para trabajar con varios efectos en presentaciones de Microsoft PowerPoint.

## Clases

| Clase | Descripción |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Representa un efecto Alpha Bi-Level. Los valores de Alpha (Opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores de alpha mayores o iguales al umbral se cambian a 100% (totalmente opaco). |
| [AlphaCeiling](./alphaceiling) | Representa un efecto Alpha Ceiling. Los valores de Alpha (opacidad) mayores que cero se cambian a 100%. En otras palabras, cualquier cosa parcialmente opaca se vuelve totalmente opaca. |
| [AlphaFloor](./alphafloor) | Representa un efecto Alpha Floor. Los valores de Alpha (opacidad) menores que 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve totalmente transparente. |
| [AlphaInverse](./alphainverse) | Representa un efecto Alpha Inverse. Los valores de Alpha (opacidad) se invierten restando de 100%. |
| [AlphaModulate](./alphamodulate) | Representa un efecto Alpha Modulate. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. El contenedor del efecto especifica un efecto que contiene valores alfa para modular. |
| [AlphaModulateFixed](./alphamodulatefixed) | Representa un efecto Alpha Modulate Fixed. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. |
| [AlphaReplace](./alphareplace) | Representa un efecto Alpha Replace. Los valores de alpha (opacidad) del efecto se reemplazan por un alpha fijo. |
| [BiLevel](./bilevel) | Representa un efecto Bi-Level (blanco/negro). Los colores de entrada cuya luminancia es menor que el valor umbral especificado se cambian a negro. Los colores de entrada cuya luminancia es mayor o igual al valor especificado se establecen en blanco. Los valores de efecto alpha no se ven afectados por este efecto. |
| [Blur](./blur) | Representa un efecto Blur que se aplica a toda la forma, incluido su relleno. Todos los canales de color, incluido el alpha, se ven afectados. |
| [ColorChange](./colorchange) | Representa un efecto de Cambio de Color. Las instancias de FromColor se reemplazan con instancias de ToColor. |
| [ColorReplace](./colorreplace) | Representa un efecto de Reemplazo de Color. Todos los colores del efecto se cambian a un color fijo. Los valores de alpha no se ven afectados. |
| [Duotone](./duotone) | Representa un efecto Duotone. Para cada píxel, combina Color1 y Color2 mediante una interpolación lineal para determinar el nuevo color para ese píxel. |
| [EffectFactory](./effectfactory) | Permite crear efectos |
| [FillOverlay](./filloverlay) | Representa un efecto Fill Overlay. Se puede usar un relleno superpuesto para especificar un relleno adicional para un objeto y combinar los dos rellenos. |
| [Glow](./glow) | Representa un efecto Glow, en el cual se agrega un contorno borroso de color fuera de los bordes del objeto. |
| [GrayScale](./grayscale) | Representa un efecto de Escala de Grises. Convierte todos los valores de color del efecto en un tono de gris, correspondiente a su luminancia. Los valores de alpha (opacidad) del efecto no se ven afectados. |
| [HSL](./hsl) | Representa un efecto de Tono/Saturación/Luminancia. El tono, la saturación y la luminancia pueden ajustarse cada uno en relación con su valor actual. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Objeto inmutable que representa una colección de efectos de transformación de imagen efectivos de solo lectura. |
| [ImageTransformOperation](./imagetransformoperation) | Representa un efecto de transformación de imagen abstracto. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Representa una colección de efectos aplicados a una imagen. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Permite crear operaciones de transformación de imágenes |
| [InnerShadow](./innershadow) | Representa un efecto de Sombra Interna. |
| [Luminance](./luminance) | Representa un efecto de Luminancia. El brillo desplaza linealmente todos los colores más cerca de blanco o negro. El contraste escala todos los colores para estar más cerca o más separados. |
| [OuterShadow](./outershadow) | Representa un efecto de Sombra Externa. |
| [PresetShadow](./presetshadow) | Representa un efecto de Sombra Preestablecida. |
| [Reflection](./reflection) | Representa un efecto de Reflexión. |
| [SoftEdge](./softedge) | Representa un efecto de borde suave. Los bordes de la forma se desenfocan, mientras que el relleno no se ve afectado. |
| [Tint](./tint) | Representa un efecto de Tint. Desplaza los valores de color del efecto hacia/alejado del tono en la cantidad especificada. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Representa un efecto Alpha Bi-Level. Los valores de Alpha (Opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores de alpha mayores o iguales al umbral se cambian a 100% (totalmente opaco). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Objeto inmutable que representa un efecto Alpha Bi-Level. Los valores de Alpha (Opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores de alpha mayores o iguales al umbral se cambian a 100% (totalmente opaco). |
| [IAlphaCeiling](./ialphaceiling) | Representa un efecto Alpha Ceiling. Los valores de Alpha (opacidad) mayores que cero se cambian a 100%. En otras palabras, cualquier cosa parcialmente opaca se vuelve totalmente opaca. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Objeto inmutable que representa un efecto Alpha Ceiling. Los valores de Alpha (opacidad) mayores que cero se cambian a 100%. En otras palabras, cualquier cosa parcialmente opaca se vuelve totalmente opaca. |
| [IAlphaFloor](./ialphafloor) | Representa un efecto Alpha Floor. Los valores de Alpha (opacidad) menores que 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve totalmente transparente. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Objeto inmutable que representa un efecto Alpha Floor. Los valores de Alpha (opacidad) menores que 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve totalmente transparente. |
| [IAlphaInverse](./ialphainverse) | Representa un efecto Alpha Inverse. Los valores de Alpha (opacidad) se invierten restando de 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Objeto inmutable que representa un efecto Alpha Inverse. Los valores de Alpha (opacidad) se invierten restando de 100%. |
| [IAlphaModulate](./ialphamodulate) | Representa un efecto Alpha Modulate. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. El contenedor del efecto especifica un efecto que contiene valores alfa para modular. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Objeto inmutable que representa un efecto Alpha Modulate. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. El contenedor del efecto especifica un efecto que contiene valores alfa para modular. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Representa un efecto Alpha Modulate Fixed. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Objeto inmutable que representa un efecto Alpha Modulate Fixed. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. |
| [IAlphaReplace](./ialphareplace) | Representa la interfaz base IImageTransformOperation. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Objeto inmutable que representa un efecto Alpha Replace. Los valores de alpha (opacidad) del efecto se reemplazan por un alpha fijo. |
| [IBiLevel](./ibilevel) | Representa la interfaz base IImageTransformOperation. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Objeto inmutable que representa un efecto Bi-Level (blanco/negro). Los colores de entrada cuya luminancia es menor que el valor umbral especificado se cambian a negro. Los colores de entrada cuya luminancia son mayores o iguales al valor especificado se establecen en blanco. Los valores de efecto alpha no se ven afectados por este efecto. |
| [IBlur](./iblur) | Representa un efecto Blur que se aplica a toda la forma, incluido su relleno. Todos los canales de color, incluido el alpha, se ven afectados. |
| [IBlurEffectiveData](./iblureffectivedata) | Objeto inmutable que representa un efecto Blur que se aplica a toda la forma, incluido su relleno. Todos los canales de color, incluido el alpha, se ven afectados. |
| [IColorChange](./icolorchange) | Representa un efecto de Cambio de Color. Las instancias de FromColor se reemplazan con instancias de ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Objeto inmutable que representa un efecto de Cambio de Color. Las instancias de FromColor se reemplazan con instancias de ToColor. |
| [IColorReplace](./icolorreplace) | Representa un efecto de Reemplazo de Color. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Objeto inmutable que representa un efecto de Reemplazo de Color. Todos los colores del efecto se cambian a un color fijo. Los valores de alpha no se ven afectados. |
| [IDuotone](./iduotone) | Representa un efecto Duotone. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Objeto inmutable que representa un efecto Duotone. Para cada píxel, combina clr1 y clr2 mediante una interpolación lineal para determinar el nuevo color para ese píxel. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Clase base para objetos inmutables, que representan un efecto. |
| [IEffectFactory](./ieffectfactory) | Permite crear instancias de efectos |
| [IFillOverlay](./ifilloverlay) | Representa un efecto Fill Overlay. Se puede usar un relleno superpuesto para especificar un relleno adicional para un objeto y combinar los dos rellenos. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Objeto inmutable que representa un efecto Fill Overlay. Se puede usar un relleno superpuesto para especificar un relleno adicional para un objeto y combinar los dos rellenos. |
| [IGlow](./iglow) | Representa un efecto Glow, en el cual se agrega un contorno borroso de color fuera de los bordes del objeto. |
| [IGlowEffectiveData](./igloweffectivedata) | Objeto inmutable que representa un efecto Glow, en el cual se agrega un contorno borroso de color fuera de los bordes del objeto. |
| [IGrayScale](./igrayscale) | Representa la interfaz IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Objeto inmutable que representa un efecto de Escala de Grises. Convierte todos los valores de color del efecto en un tono de gris, correspondiente a su luminancia. Los valores de alpha (opacidad) del efecto no se ven afectados. |
| [IHSL](./ihsl) | Representa un efecto de Tono/Saturación/Luminancia. El tono, la saturación y la luminancia pueden ajustarse cada uno en relación con su valor actual. |
| [IHSLEffectiveData](./ihsleffectivedata) | Representa un efecto de Tono/Saturación/Luminancia. El tono, la saturación y la luminancia pueden ajustarse cada uno en relación con su valor actual. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Objeto inmutable que representa una colección de efectos de transformación de imagen efectivos de solo lectura. |
| [IImageTransformOperation](./iimagetransformoperation) | Representa un efecto de transformación de imagen abstracto. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Representa una colección de efectos aplicados a una imagen. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Permite crear instancias de efectos de imagen |
| [IInnerShadow](./iinnershadow) | Representa un efecto de sombra interna. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Objeto inmutable que representa un efecto de sombra interna. |
| [ILuminance](./iluminance) | Representa un efecto de Luminancia. El brillo desplaza linealmente todos los colores más cerca de blanco o negro. El contraste escala todos los colores para estar más cerca o más separados. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Representa un efecto de Luminancia. El brillo desplaza linealmente todos los colores más cerca de blanco o negro. El contraste escala todos los colores para estar más cerca o más separados. |
| [IOuterShadow](./ioutershadow) | Representa un efecto de Sombra Externa. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Objeto inmutable que representa un efecto de Sombra Externa. |
| [IPresetShadow](./ipresetshadow) | Representa un efecto de Sombra Preestablecida. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Objeto inmutable que representa un efecto de Sombra Preestablecida. |
| [IReflection](./ireflection) | Representa un efecto de reflexión. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Objeto inmutable que representa un efecto de Reflexión. |
| [ISoftEdge](./isoftedge) | Representa un efecto de Borde Suave. Los bordes de la forma se desenfocan, mientras que el relleno no se ve afectado. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Objeto inmutable que representa un efecto de borde suave. Los bordes de la forma se desenfocan, mientras que el relleno no se ve afectado. |
| [ITint](./itint) | Representa un efecto de Tint. Desplaza los valores de color del efecto hacia/alejado del tono en la cantidad especificada. |
| [ITintEffectiveData](./itinteffectivedata) | Objeto inmutable que representa un efecto de Tint. Desplaza los valores de color del efecto hacia/alejado del tono en la cantidad especificada. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->