---
title: Aspose.Slides.Effects
second_title: Referencia de la API de Aspose.Slides para .NET
description: Contiene clases para trabajar con varios efectos en presentaciones de Microsoft PowerPoint.
type: docs
weight: 50
url: /es/net/aspose.slides.effects/
---
Contiene clases para trabajar con varios efectos en presentaciones de Microsoft PowerPoint.

## Clases

| Clase | Descripción |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Representa un efecto Alpha Bi-Level. Los valores alfa (opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores alfa mayores o iguales al umbral se cambian a 100% (totalmente opaco). |
| [AlphaCeiling](./alphaceiling) | Representa un efecto de techo alfa. Los valores alfa (opacidad) superiores a cero se cambian a 100%. En otras palabras, cualquier cosa parcialmente opaca se vuelve completamente opaca. |
| [AlphaFloor](./alphafloor) | Representa un efecto Alpha Floor. Los valores alfa (opacidad) inferiores al 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve completamente transparente. |
| [AlphaInverse](./alphainverse) | Representa un efecto alfa inverso. Los valores alfa (opacidad) se invierten restando del 100%. |
| [AlphaModulate](./alphamodulate) | Representa un efecto de modulación alfa. Los valores alfa (opacidad) del efecto se multiplican por un porcentaje fijo. El contenedor de efectos especifica un efecto que contiene valores alfa para modular. |
| [AlphaModulateFixed](./alphamodulatefixed) | Representa un efecto fijo de modulación alfa. Los valores de efecto alfa (opacidad) se multiplican por un porcentaje fijo. |
| [AlphaReplace](./alphareplace) | Representa y el efecto Alpha Replace. Los valores del efecto alfa (opacidad) se reemplazan por un alfa fijo. |
| [BiLevel](./bilevel) | Representa un efecto de dos niveles (negro/blanco). Los colores de entrada cuya luminancia es menor que el valor de umbral especificado se cambian a negro. Los colores de entrada cuya luminancia es mayor o igual que el valor especificado se establecen en blanco. los valores del efecto alfa no se ven afectados por este efecto. |
| [Blur](./blur) | Representa un efecto de desenfoque que se aplica a toda la forma, incluido su relleno. Todos los canales de color, incluido el alfa, se ven afectados. |
| [ColorChange](./colorchange) | Representa un efecto de cambio de color. Las instancias de FromColor se reemplazan con instancias de ToColor. |
| [ColorReplace](./colorreplace) | Representa un efecto de reemplazo de color. Todos los colores del efecto cambian a un color fijo. Los valores alfa no se ven afectados. |
| [Duotone](./duotone) | Representa un efecto Duotono. Para cada píxel, combina Color1 y Color2 a través de una interpolación lineal para determinar el nuevo color para ese píxel. |
| [EffectFactory](./effectfactory) | Permite crear efectos |
| [FillOverlay](./filloverlay) | Representa un efecto de superposición de relleno. Se puede usar una superposición de relleno para especificar un relleno adicional para un objeto y combinar los dos rellenos. |
| [Glow](./glow) | Representa un efecto Resplandor, en el que se agrega un contorno borroso de color fuera de los bordes del objeto. |
| [GrayScale](./grayscale) | Representa un efecto de escala de grises. Convierte todos los valores de color del efecto a un tono de gris, correspondiente a su luminancia. Los valores de efecto alfa (opacidad) no se ven afectados. |
| [HSL](./hsl) | Representa un efecto de Tono/Saturación/Luminancia. El tono, la saturación y la luminancia se pueden ajustar en relación con su valor actual. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Objeto inmutable que representa una colección de solo lectura de efectos de transformación de imagen efectivos. |
| [ImageTransformOperation](./imagetransformoperation) | Representa el efecto de transformación de imagen abstracta. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Representa una colección de efectos aplicados a una imagen. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Permite crear operaciones de transformación de imágenes |
| [InnerShadow](./innershadow) | Representa un efecto de Sombra Interior. |
| [Luminance](./luminance) | Representa un efecto de luminancia. El brillo cambia linealmente todos los colores más cerca del blanco o el negro. El contraste escala todos los colores para que estén más cerca o más separados. |
| [OuterShadow](./outershadow) | Representa un efecto de Sombra Exterior. |
| [PresetShadow](./presetshadow) | Representa un efecto de sombra preestablecido. |
| [Reflection](./reflection) | Representa un efecto de Reflejo. |
| [SoftEdge](./softedge) | Representa un efecto de borde suave. Los bordes de la forma se difuminan, mientras que el relleno no se ve afectado. |
| [Tint](./tint) | Representa un efecto de Matiz. Cambia los valores de color del efecto hacia/alejando del matiz en la cantidad especificada. |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Representa un efecto Alpha Bi-Level. Los valores alfa (opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores alfa mayores o iguales al umbral se cambian a 100% (totalmente opaco). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Objeto inmutable que representa un efecto Alpha Bi-Level. Los valores alfa (opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores alfa mayores o iguales al umbral se cambian a 100% (totalmente opaco). |
| [IAlphaCeiling](./ialphaceiling) | Representa un efecto de techo alfa. Los valores alfa (opacidad) superiores a cero se cambian a 100%. En otras palabras, cualquier cosa parcialmente opaca se vuelve completamente opaca. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Objeto inmutable que representa un efecto de techo alfa. Los valores alfa (opacidad) mayores que cero se cambian a 100%. En otras palabras, cualquier cosa parcialmente opaca se vuelve completamente opaca. |
| [IAlphaFloor](./ialphafloor) | Representa un efecto Alpha Floor. Los valores alfa (opacidad) inferiores al 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve completamente transparente. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Objeto inmutable que representa un efecto Alpha Floor. Los valores alfa (opacidad) inferiores al 100% se cambian a cero. En otras palabras, cualquier cosa parcialmente transparente se vuelve completamente transparente. |
| [IAlphaInverse](./ialphainverse) | Representa un efecto alfa inverso. Los valores alfa (opacidad) se invierten restando del 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Objeto inmutable que representa un efecto Alfa Inverso. Los valores alfa (opacidad) se invierten restando del 100%. |
| [IAlphaModulate](./ialphamodulate) | Representa un efecto de modulación alfa. Los valores alfa (opacidad) del efecto se multiplican por un porcentaje fijo. El contenedor de efectos especifica un efecto que contiene valores alfa para modular. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Objeto inmutable que representa un efecto de modulación alfa. Los valores alfa (opacidad) del efecto se multiplican por un porcentaje fijo. El contenedor de efectos especifica un efecto que contiene valores alfa para modular. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Representa un efecto fijo de modulación alfa. Los valores de efecto alfa (opacidad) se multiplican por un porcentaje fijo. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Objeto inmutable que representa un efecto fijo de modulación alfa. Los valores de efecto alfa (opacidad) se multiplican por un porcentaje fijo. |
| [IAlphaReplace](./ialphareplace) | Representa la interfaz base IImageTransformOperation. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Objeto inmutable que representa un efecto Alpha Replace. Los valores del efecto alfa (opacidad) se reemplazan por un alfa fijo. |
| [IBiLevel](./ibilevel) | Representa la interfaz base IImageTransformOperation. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Objeto inmutable que representa un efecto de dos niveles (blanco/negro). Los colores de entrada cuya luminancia es menor que el valor de umbral especificado se cambian a negro. Los colores de entrada cuya luminancia es mayor o igual que el valor especificado se establecen en blanco . Los valores del efecto alfa no se ven afectados por este efecto. |
| [IBlur](./iblur) | Representa un efecto de desenfoque que se aplica a toda la forma, incluido su relleno. Todos los canales de color, incluido el alfa, se ven afectados. |
| [IBlurEffectiveData](./iblureffectivedata) | Objeto inmutable que representa un efecto de desenfoque que se aplica a toda la forma, incluido su relleno. Todos los canales de color, incluido el alfa, se ven afectados. |
| [IColorChange](./icolorchange) | Representa un efecto de cambio de color. Las instancias de FromColor se reemplazan con instancias de ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Objeto inmutable que representa un efecto de cambio de color. Las instancias de FromColor se reemplazan con instancias de ToColor. |
| [IColorReplace](./icolorreplace) | Representa un efecto de reemplazo de color. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Objeto inmutable que representa un efecto de reemplazo de color. Todos los colores del efecto cambian a un color fijo. Los valores alfa no se ven afectados. |
| [IDuotone](./iduotone) | Representa un efecto Duotono. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Objeto inmutable que representa un efecto Duotono. Para cada píxel, combina clr1 y clr2 a través de una interpolación lineal para determinar el nuevo color para ese píxel. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Clase base para objetos inmutables, que representan efecto. |
| [IEffectFactory](./ieffectfactory) | Permite crear instancias de efectos |
| [IFillOverlay](./ifilloverlay) | Representa un efecto de superposición de relleno. Se puede usar una superposición de relleno para especificar un relleno adicional para un objeto y combinar los dos rellenos. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Objeto inmutable que representa un efecto de superposición de relleno. Se puede usar una superposición de relleno para especificar un relleno adicional para un objeto y combinar los dos rellenos. |
| [IGlow](./iglow) | Representa un efecto Resplandor, en el que se agrega un contorno borroso de color fuera de los bordes del objeto. |
| [IGlowEffectiveData](./igloweffectivedata) | Objeto inmutable que representa un efecto Glow, en el que se añade un contorno difuminado de color fuera de los bordes del objeto. |
| [IGrayScale](./igrayscale) | Representa la interfaz IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Objeto inmutable que representa un efecto de escala de grises. Convierte todos los valores de color del efecto a un tono de gris, correspondiente a su luminancia. Los valores de efecto alfa (opacidad) no se ven afectados. |
| [IHSL](./ihsl) | Representa un efecto de Tono/Saturación/Luminancia. El tono, la saturación y la luminancia se pueden ajustar en relación con su valor actual. |
| [IHSLEffectiveData](./ihsleffectivedata) | Representa un efecto de Tono/Saturación/Luminancia. El tono, la saturación y la luminancia se pueden ajustar en relación con su valor actual. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Objeto inmutable que representa una colección de solo lectura de efectos de transformación de imagen efectivos. |
| [IImageTransformOperation](./iimagetransformoperation) | Representa el efecto de transformación de imagen abstracta. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Representa una colección de efectos aplicados a una imagen. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Permite crear instancias de efectos de imagen |
| [IInnerShadow](./iinnershadow) | Representa un efecto de sombra interior. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Objeto inmutable que representa un efecto de sombra interior. |
| [ILuminance](./iluminance) | Representa un efecto de luminancia. El brillo cambia linealmente todos los colores más cerca del blanco o el negro. El contraste escala todos los colores para que estén más cerca o más separados. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Representa un efecto de luminancia. El brillo cambia linealmente todos los colores más cerca del blanco o el negro. El contraste escala todos los colores para que estén más cerca o más separados. |
| [IOuterShadow](./ioutershadow) | Representa un efecto de Sombra Exterior. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Objeto inmutable que representa un efecto de Sombra Exterior. |
| [IPresetShadow](./ipresetshadow) | Representa un efecto de sombra preestablecido. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Objeto inmutable que representa un efecto Preset Shadow. |
| [IReflection](./ireflection) | Representa un efecto de reflejo. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Objeto inmutable que representa un efecto de Reflejo. |
| [ISoftEdge](./isoftedge) | Representa un efecto de borde suave. Los bordes de la forma se difuminan, mientras que el relleno no se ve afectado. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Objeto inmutable que representa un efecto de borde suave. Los bordes de la forma se difuminan, mientras que el relleno no se ve afectado. |
| [ITint](./itint) | Representa un efecto de Matiz. Cambia los valores de color del efecto hacia/alejando del matiz en la cantidad especificada. |
| [ITintEffectiveData](./itinteffectivedata) | Objeto inmutable que representa un efecto Tint. Cambia los valores de color del efecto hacia/alejando del matiz en la cantidad especificada. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
