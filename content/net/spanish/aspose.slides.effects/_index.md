---
title: Aspose.Slides.Effects
second_title: Referencia de API de Aspose.Sildes para .NET
description: Contiene clases para trabajar con varios efectos en presentaciones de Microsoft PowerPoint.
type: docs
weight: 50
url: /es/aspose.slides.effects/
---

Contiene clases para trabajar con varios efectos en presentaciones de Microsoft PowerPoint.

## Clases

| Clase | Descripción |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Representa un efecto de Alpha Bi-Level. Los valores de Alpha (opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores de alpha mayores o iguales al umbral se cambian a 100% (totalmente opaco). |
| [AlphaCeiling](./alphaceiling) | Representa un efecto de Alpha Ceiling. Los valores de Alpha (opacidad) mayores que cero se cambian a 100%. En otras palabras, cualquier cosa parcialmente opaca se vuelve totalmente opaca. |
| [AlphaFloor](./alphafloor) | Representa un efecto de Alpha Floor. Los valores de Alpha (opacidad) menores que 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve totalmente transparente. |
| [AlphaInverse](./alphainverse) | Representa un efecto de Alpha Inverse. Los valores de Alpha (opacidad) se invierten restando de 100%. |
| [AlphaModulate](./alphamodulate) | Representa un efecto de Alpha Modulate. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. El contenedor del efecto especifica un efecto que contiene valores de alpha para modular. |
| [AlphaModulateFixed](./alphamodulatefixed) | Representa un efecto de Alpha Modulate Fixed. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. |
| [AlphaReplace](./alphareplace) | Representa un efecto de Alpha Replace. Los valores de alpha (opacidad) del efecto se reemplazan por un alpha fijo. |
| [BiLevel](./bilevel) | Representa un efecto Bi-Level (blanco/negro). Los colores de entrada cuya luminancia es menor que el umbral especificado se cambian a negro. Los colores de entrada cuya luminancia es mayor o igual al valor especificado se establecen en blanco. Los valores del efecto alpha no se ven afectados por este efecto. |
| [Blur](./blur) | Representa un efecto de Blur que se aplica a toda la forma, incluyendo su relleno. Todos los canales de color, incluyendo alpha, se ven afectados. |
| [ColorChange](./colorchange) | Representa un efecto de Color Change. Las instancias de FromColor se reemplazan con instancias de ToColor. |
| [ColorReplace](./colorreplace) | Representa un efecto de Color Replacement. Todos los colores del efecto se cambian a un color fijo. Los valores alpha no se ven afectados. |
| [Duotone](./duotone) | Representa un efecto Duotone. Para cada píxel, combina Color1 y Color2 a través de una interpolación lineal para determinar el nuevo color para ese píxel. |
| [EffectFactory](./effectfactory) | Permite crear efectos |
| [FillOverlay](./filloverlay) | Representa un efecto de Fill Overlay. Se puede usar un relleno superpuesto para especificar un relleno adicional para un objeto y mezclar los dos rellenos juntos. |
| [Glow](./glow) | Representa un efecto de Glow, en el que se agrega un contorno desenfocado de color fuera de los bordes del objeto. |
| [GrayScale](./grayscale) | Representa un efecto de Gray Scale. Convierte todos los valores de color del efecto a un tono de gris, correspondiente a su luminancia. Los valores de alpha (opacidad) del efecto no se ven afectados. |
| [HSL](./hsl) | Representa un efecto de Hue/Saturation/Luminance. El matiz, la saturación y la luminancia se pueden ajustar en relación con su valor actual. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Objeto inmutable que representa una colección de efectos de transformación de imagen efectivos en modo solo lectura. |
| [ImageTransformOperation](./imagetransformoperation) | Representa un efecto de transformación de imagen abstracto. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Representa una colección de efectos aplicados a una imagen. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Permite crear operaciones de transformación de imagen |
| [InnerShadow](./innershadow) | Representa un efecto de Inner Shadow. |
| [Luminance](./luminance) | Representa un efecto de Luminance. El brillo desplaza linealmente todos los colores más cerca de blanco o negro. El contraste escala todos los colores para que estén más cerca o más separados. |
| [OuterShadow](./outershadow) | Representa un efecto de Outer Shadow. |
| [PresetShadow](./presetshadow) | Representa un efecto de Preset Shadow. |
| [Reflection](./reflection) | Representa un efecto de Reflection. |
| [SoftEdge](./softedge) | Representa un efecto de Soft Edge. Los bordes de la forma se difuminan, mientras que el relleno no se ve afectado. |
| [Tint](./tint) | Representa un efecto de Tint. Desplaza los valores de color del efecto hacia/alejados del matiz por la cantidad especificada. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Representa un efecto de Alpha Bi-Level. Los valores de Alpha (opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores de alpha mayores o iguales al umbral se cambian a 100% (totalmente opaco). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Objeto inmutable que representa un efecto de Alpha Bi-Level. Los valores de Alpha (opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores de alpha mayores o iguales al umbral se cambian a 100% (totalmente opaco). |
| [IAlphaCeiling](./ialphaceiling) | Representa un efecto de Alpha Ceiling. Los valores de Alpha (opacidad) mayores que cero se cambian a 100%. En otras palabras, cualquier cosa parcialmente opaca se vuelve totalmente opaca. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Objeto inmutable que representa un efecto de Alpha Ceiling. Los valores de Alpha (opacidad) mayores que cero se cambian a 100%. En otras palabras, cualquier cosa parcialmente opaca se vuelve totalmente opaca. |
| [IAlphaFloor](./ialphafloor) | Representa un efecto de Alpha Floor. Los valores de Alpha (opacidad) menores que 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve totalmente transparente. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Objeto inmutable que representa un efecto de Alpha Floor. Los valores de Alpha (opacidad) menores que 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve totalmente transparente. |
| [IAlphaInverse](./ialphainverse) | Representa un efecto de Alpha Inverse. Los valores de Alpha (opacidad) se invierten restando de 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Objeto inmutable que representa un efecto de Alpha Inverse. Los valores de Alpha (opacidad) se invierten restando de 100%. |
| [IAlphaModulate](./ialphamodulate) | Representa un efecto de Alpha Modulate. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. El contenedor del efecto especifica un efecto que contiene valores de alpha para modular. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Objeto inmutable que representa un efecto de Alpha Modulate. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. El contenedor del efecto especifica un efecto que contiene valores de alpha para modular. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Representa un efecto de Alpha Modulate Fixed. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Objeto inmutable que representa un efecto de Alpha Modulate Fixed. Los valores de alpha (opacidad) del efecto se multiplican por un porcentaje fijo. |
| [IAlphaReplace](./ialphareplace) | Representa la interfaz base IImageTransformOperation. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Objeto inmutable que representa un efecto de Alpha Replace. Los valores de alpha (opacidad) del efecto se reemplazan por un alpha fijo. |
| [IBiLevel](./ibilevel) | Representa la interfaz base IImageTransformOperation. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Objeto inmutable que representa un efecto Bi-Level (blanco/negro). Los colores de entrada cuya luminancia es menor que el umbral especificado se cambian a negro. Los colores de entrada cuya luminancia es mayor o igual al valor especificado se establecen en blanco. Los valores del efecto alpha no se ven afectados por este efecto. |
| [IBlur](./iblur) | Representa un efecto de Blur que se aplica a toda la forma, incluyendo su relleno. Todos los canales de color, incluyendo alpha, se ven afectados. |
| [IBlurEffectiveData](./iblureffectivedata) | Objeto inmutable que representa un efecto de Blur que se aplica a toda la forma, incluyendo su relleno. Todos los canales de color, incluyendo alpha, se ven afectados. |
| [IColorChange](./icolorchange) | Representa un efecto de Color Change. Las instancias de FromColor se reemplazan con instancias de ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Objeto inmutable que representa un efecto de Color Change. Las instancias de FromColor se reemplazan con instancias de ToColor. |
| [IColorReplace](./icolorreplace) | Representa un efecto de Color Replacement. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Objeto inmutable que representa un efecto de Color Replacement. Todos los colores del efecto se cambian a un color fijo. Los valores alpha no se ven afectados. |
| [IDuotone](./iduotone) | Representa un efecto Duotone. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Objeto inmutable que representa un efecto Duotone. Para cada píxel, combina clr1 y clr2 a través de una interpolación lineal para determinar el nuevo color para ese píxel. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Clase base para objetos inmutables, que representan efectos. |
| [IEffectFactory](./ieffectfactory) | Permite crear instancias de efectos |
| [IFillOverlay](./ifilloverlay) | Representa un efecto de Fill Overlay. Se puede usar un relleno superpuesto para especificar un relleno adicional para un objeto y mezclar los dos rellenos juntos. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Objeto inmutable que representa un efecto de Fill Overlay. Se puede usar un relleno superpuesto para especificar un relleno adicional para un objeto y mezclar los dos rellenos juntos. |
| [IGlow](./iglow) | Representa un efecto de Glow, en el que se agrega un contorno desenfocado de color fuera de los bordes del objeto. |
| [IGlowEffectiveData](./igloweffectivedata) | Objeto inmutable que representa un efecto de Glow, en el que se agrega un contorno desenfocado de color fuera de los bordes del objeto. |
| [IGrayScale](./igrayscale) | Representa la interfaz IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Objeto inmutable que representa un efecto de Gray Scale. Convierte todos los valores de color del efecto a un tono de gris, correspondiente a su luminancia. Los valores de alpha (opacidad) del efecto no se ven afectados. |
| [IHSL](./ihsl) | Representa un efecto de Hue/Saturation/Luminance. El matiz, la saturación y la luminancia se pueden ajustar en relación con su valor actual. |
| [IHSLEffectiveData](./ihsleffectivedata) | Representa un efecto de Hue/Saturation/Luminance. El matiz, la saturación y la luminancia se pueden ajustar en relación con su valor actual. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Objeto inmutable que representa una colección de efectos de transformación de imagen efectivos en modo solo lectura. |
| [IImageTransformOperation](./iimagetransformoperation) | Representa un efecto de transformación de imagen abstracto. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Representa una colección de efectos aplicados a una imagen. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Permite crear instancias de efectos de imagen |
| [IInnerShadow](./iinnershadow) | Representa un efecto de sombra interna. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Objeto inmutable que representa un efecto de sombra interna. |
| [ILuminance](./iluminance) | Representa un efecto de Luminance. El brillo desplaza linealmente todos los colores más cerca de blanco o negro. El contraste escala todos los colores para que estén más cerca o más separados. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Representa un efecto de Luminance. El brillo desplaza linealmente todos los colores más cerca de blanco o negro. El contraste escala todos los colores para que estén más cerca o más separados. |
| [IOuterShadow](./ioutershadow) | Representa un efecto de Outer Shadow. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Objeto inmutable que representa un efecto de Outer Shadow. |
| [IPresetShadow](./ipresetshadow) | Representa un efecto de Preset Shadow. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Objeto inmutable que representa un efecto de Preset Shadow. |
| [IReflection](./ireflection) | Representa un efecto de reflexión. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Objeto inmutable que representa un efecto de Reflection. |
| [ISoftEdge](./isoftedge) | Representa un efecto de Soft Edge. Los bordes de la forma se difuminan, mientras que el relleno no se ve afectado. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Objeto inmutable que representa un efecto de soft edge. Los bordes de la forma se difuminan, mientras que el relleno no se ve afectado. |
| [ITint](./itint) | Representa un efecto de Tint. Desplaza los valores de color del efecto hacia/alejados del matiz por la cantidad especificada. |
| [ITintEffectiveData](./itinteffectivedata) | Objeto inmutable que representa un efecto de Tint. Desplaza los valores de color del efecto hacia/alejados del matiz por la cantidad especificada. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->