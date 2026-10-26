---
title: Aspose.Slides.Effects
second_title: Riferimento API .NET di Aspose.Sildes
description: Contiene classi per lavorare con vari effetti nelle presentazioni Microsoft PowerPoint.
type: docs
weight: 60
url: /it/aspose.slides.effects/
---
Contiene classi per lavorare con vari effetti nelle presentazioni Microsoft PowerPoint.

## Classi

| Class | Description |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Rappresenta un effetto Alpha Bi-Level. I valori Alpha (Opacity) inferiori alla soglia vengono impostati a 0 (completamente trasparente) e i valori alpha maggiori o uguali alla soglia vengono impostati al 100 % (completamente opaco). |
| [AlphaCeiling](./alphaceiling) | Rappresenta un effetto Alpha Ceiling. I valori Alpha (opacity) maggiori di zero vengono impostati al 100 %. In altre parole, qualsiasi elemento parzialmente opaco diventa completamente opaco. |
| [AlphaFloor](./alphafloor) | Rappresenta un effetto Alpha Floor. I valori Alpha (opacity) inferiori al 100 % vengono impostati a zero. In altre parole, qualsiasi elemento parzialmente trasparente diventa completamente trasparente. |
| [AlphaInverse](./alphainverse) | Rappresenta un effetto Alpha Inverse. I valori Alpha (opacity) vengono invertiti sottraendoli dal 100 %. |
| [AlphaModulate](./alphamodulate) | Rappresenta un effetto Alpha Modulate. I valori alpha (opacity) dell'effetto vengono moltiplicati per una percentuale fissa. Il contenitore dell'effetto specifica un effetto contenente valori alpha da modulare. |
| [AlphaModulateFixed](./alphamodulatefixed) | Rappresenta un effetto Alpha Modulate Fixed. I valori alpha (opacity) dell'effetto vengono moltiplicati per una percentuale fissa. |
| [AlphaReplace](./alphareplace) | Rappresenta un effetto Alpha Replace. I valori alpha (opacity) dell'effetto vengono sostituiti da un alpha fisso. |
| [BiLevel](./bilevel) | Rappresenta un effetto Bi-Level (black/white). I colori di input la cui luminanza è inferiore al valore di soglia specificato vengono trasformati in nero. I colori di input la cui luminanza è maggiore o uguale al valore specificato vengono impostati a bianco. I valori alpha dell'effetto non sono influenzati da questo effetto. |
| [Blur](./blur) | Rappresenta un effetto Blur applicato all'intera forma, includendo il riempimento. Tutti i canali colore, incluso l'alpha, sono influenzati. |
| [BrightnessContrast](./brightnesscontrast) | Rappresenta un effetto BrightnessContrast. Regola luminosità e contrasto |
| [ColorChange](./colorchange) | Rappresenta un effetto Color Change. Le istanze di FromColor vengono sostituite con istanze di ToColor. |
| [ColorReplace](./colorreplace) | Rappresenta un effetto Color Replacement. Tutti i colori dell'effetto vengono cambiati in un colore fisso. I valori alpha non sono influenzati. |
| [Duotone](./duotone) | Rappresenta un effetto Duotone. Per ogni pixel, combina Color1 e Color2 mediante interpolazione lineare per determinare il nuovo colore del pixel. |
| [EffectFactory](./effectfactory) | Consente di creare effetti |
| [FillOverlay](./filloverlay) | Rappresenta un effetto Fill Overlay. Un overlay di riempimento può essere usato per specificare un riempimento aggiuntivo per un oggetto e mescolare i due riempimenti insieme. |
| [Glow](./glow) | Rappresenta un effetto Glow, in cui un contorno sfocato di colore viene aggiunto al di fuori dei bordi dell'oggetto. |
| [GrayScale](./grayscale) | Rappresenta un effetto Gray Scale. Converte tutti i valori colore dell'effetto in una tonalità di grigio, corrispondente alla loro luminanza. I valori alpha (opacity) dell'effetto non sono influenzati. |
| [HSL](./hsl) | Rappresenta un effetto Hue/Saturation/Luminance. La tonalità, la saturazione e la luminanza possono essere regolate individualmente rispetto al loro valore attuale. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Oggetto immutabile che rappresenta una collezione readonly di effetti di trasformazione immagine effettivi. |
| [ImageTransformOperation](./imagetransformoperation) | Rappresenta un effetto di trasformazione immagine astratto. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Rappresenta una collezione di effetti applicati a un'immagine. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Consente di creare operazioni di trasformazione immagine |
| [InnerShadow](./innershadow) | Rappresenta un effetto Inner Shadow. |
| [Luminance](./luminance) | Rappresenta un effetto Luminance. La luminosità sposta linearmente tutti i colori verso il bianco o il nero. Il contrasto scala tutti i colori rendendoli più o meno distanti. |
| [OuterShadow](./outershadow) | Rappresenta un effetto Outer Shadow. |
| [PresetShadow](./presetshadow) | Rappresenta un effetto Preset Shadow. |
| [Reflection](./reflection) | Rappresenta un effetto Reflection. |
| [SoftEdge](./softedge) | Rappresenta un effetto soft edge. I bordi della forma sono sfocati, mentre il riempimento non è influenzato. |
| [Tint](./tint) | Rappresenta un effetto Tint. Sposta i valori colore dell'effetto verso/lontano dalla tonalità di un ammontare specificato. |

## Interfacce

| Interface | Description |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Rappresenta un effetto Alpha Bi-Level. I valori Alpha (Opacity) inferiori alla soglia vengono impostati a 0 (completamente trasparente) e i valori alpha maggiori o uguali alla soglia vengono impostati al 100 % (completamente opaco). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Oggetto immutabile che rappresenta un effetto Alpha Bi-Level. I valori Alpha (Opacity) inferiori alla soglia vengono impostati a 0 (completamente trasparente) e i valori alpha maggiori o uguali alla soglia vengono impostati al 100 % (completamente opaco). |
| [IAlphaCeiling](./ialphaceiling) | Rappresenta un effetto Alpha Ceiling. I valori Alpha (opacity) maggiori di zero vengono impostati al 100 %. In altre parole, qualsiasi elemento parzialmente opaco diventa completamente opaco. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Oggetto immutabile che rappresenta un effetto Alpha Ceiling. I valori Alpha (opacity) maggiori di zero vengono impostati al 100 %. In altre parole, qualsiasi elemento parzialmente opaco diventa completamente opaco. |
| [IAlphaFloor](./ialphafloor) | Rappresenta un effetto Alpha Floor. I valori Alpha (opacity) inferiori al 100 % vengono impostati a zero. In altre parole, qualsiasi elemento parzialmente trasparente diventa completamente trasparente. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Oggetto immutabile che rappresenta un effetto Alpha Floor. I valori Alpha (opacity) inferiori al 100 % vengono impostati a zero. In altre parole, qualsiasi elemento parzialmente trasparente diventa completamente trasparente. |
| [IAlphaInverse](./ialphainverse) | Rappresenta un effetto Alpha Inverse. I valori Alpha (opacity) vengono invertiti sottraendoli dal 100 %. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Oggetto immutabile che rappresenta un effetto Alpha Inverse. I valori Alpha (opacity) vengono invertiti sottraendoli dal 100 %. |
| [IAlphaModulate](./ialphamodulate) | Rappresenta un effetto Alpha Modulate. I valori alpha (opacity) dell'effetto vengono moltiplicati per una percentuale fissa. Il contenitore dell'effetto specifica un effetto contenente valori alpha da modulare. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Oggetto immutabile che rappresenta un effetto Alpha Modulate. I valori alpha (opacity) dell'effetto vengono moltiplicati per una percentuale fissa. Il contenitore dell'effetto specifica un effetto contenente valori alpha da modulare. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Rappresenta un effetto Alpha Modulate Fixed. I valori alpha (opacity) dell'effetto vengono moltiplicati per una percentuale fissa. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Oggetto immutabile che rappresenta un effetto Alpha Modulate Fixed. I valori alpha (opacity) dell'effetto vengono moltiplicati per una percentuale fissa. |
| [IAlphaReplace](./ialphareplace) | Rappresenta l'interfaccia di base IImageTransformOperation. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Oggetto immutabile che rappresenta un effetto Alpha Replace. I valori alpha (opacity) dell'effetto vengono sostituiti da un alpha fisso. |
| [IBiLevel](./ibilevel) | Rappresenta l'interfaccia di base IImageTransformOperation. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Oggetto immutabile che rappresenta un effetto Bi-Level (black/white). I colori di input la cui luminanza è inferiore al valore di soglia specificato vengono trasformati in nero. I colori di input la cui luminanza è maggiore o uguale al valore specificato vengono impostati a bianco. I valori alpha dell'effetto non sono influenzati da questo effetto. |
| [IBlur](./iblur) | Rappresenta un effetto Blur applicato all'intera forma, includendo il riempimento. Tutti i canali colore, incluso l'alpha, sono influenzati. |
| [IBlurEffectiveData](./iblureffectivedata) | Oggetto immutabile che rappresenta un effetto Blur applicato all'intera forma, includendo il riempimento. Tutti i canali colore, incluso l'alpha, sono influenzati. |
| [IBrightnessContrast](./ibrightnesscontrast) | Rappresenta un effetto BrightnessContrast. Regola luminosità e contrasto |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | Oggetto immutabile che rappresenta un effetto BrightnessContrast. Regola luminosità e contrasto |
| [IColorChange](./icolorchange) | Rappresenta un effetto Color Change. Le istanze di FromColor vengono sostituite con istanze di ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Oggetto immutabile che rappresenta un effetto Color Change. Le istanze di FromColor vengono sostituite con istanze di ToColor. |
| [IColorReplace](./icolorreplace) | Rappresenta un effetto Color Replacement. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Oggetto immutabile che rappresenta un effetto Color Replacement. Tutti i colori dell'effetto vengono cambiati in un colore fisso. I valori alpha non sono influenzati. |
| [IDuotone](./iduotone) | Rappresenta un effetto Duotone. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Oggetto immutabile che rappresenta un effetto Duotone. Per ogni pixel, combina clr1 e clr2 mediante interpolazione lineare per determinare il nuovo colore del pixel. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Classe di base per oggetti immutabili, che rappresentano un effetto. |
| [IEffectFactory](./ieffectfactory) | Consente di creare istanze di effetti |
| [IFillOverlay](./ifilloverlay) | Rappresenta un effetto Fill Overlay. Un overlay di riempimento può essere usato per specificare un riempimento aggiuntivo per un oggetto e mescolare i due riempimenti insieme. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Oggetto immutabile che rappresenta un effetto Fill Overlay. Un overlay di riempimento può essere usato per specificare un riempimento aggiuntivo per un oggetto e mescolare i due riempimenti insieme. |
| [IGlow](./iglow) | Rappresenta un effetto Glow, in cui un contorno sfocato di colore viene aggiunto al di fuori dei bordi dell'oggetto. |
| [IGlowEffectiveData](./igloweffectivedata) | Oggetto immutabile che rappresenta un effetto Glow, in cui un contorno sfocato di colore viene aggiunto al di fuori dei bordi dell'oggetto. |
| [IGrayScale](./igrayscale) | Rappresenta l'interfaccia IImageTransformOperation. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Oggetto immutabile che rappresenta un effetto Gray Scale. Converte tutti i valori colore dell'effetto in una tonalità di grigio, corrispondente alla loro luminanza. I valori alpha (opacity) dell'effetto non sono influenzati. |
| [IHSL](./ihsl) | Rappresenta un effetto Hue/Saturation/Luminance. La tonalità, la saturazione e la luminanza possono essere regolate individualmente rispetto al loro valore attuale. |
| [IHSLEffectiveData](./ihsleffectivedata) | Rappresenta un effetto Hue/Saturation/Luminance. La tonalità, la saturazione e la luminanza possono essere regolate individualmente rispetto al loro valore attuale. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Oggetto immutabile che rappresenta una collezione readonly di effetti di trasformazione immagine effettivi. |
| [IImageTransformOperation](./iimagetransformoperation) | Rappresenta un effetto di trasformazione immagine astratto. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Rappresenta una collezione di effetti applicati a un'immagine. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Consente di creare istanze di effetti immagine |
| [IInnerShadow](./iinnershadow) | Rappresenta un effetto inner shadow. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Oggetto immutabile che rappresenta un effetto inner shadow. |
| [ILuminance](./iluminance) | Rappresenta un effetto Luminance. La luminosità sposta linearmente tutti i colori verso il bianco o il nero. Il contrasto scala tutti i colori rendendoli più o meno distanti. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Rappresenta un effetto Luminance. La luminosità sposta linearmente tutti i colori verso il bianco o il nero. Il contrasto scala tutti i colori rendendoli più o meno distanti. |
| [IOuterShadow](./ioutershadow) | Rappresenta un effetto Outer Shadow. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Oggetto immutabile che rappresenta un effetto Outer Shadow. |
| [IPresetShadow](./ipresetshadow) | Rappresenta un effetto Preset Shadow. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Oggetto immutabile che rappresenta un effetto Preset Shadow. |
| [IReflection](./ireflection) | Rappresenta un effetto reflection. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Oggetto immutabile che rappresenta un effetto Reflection. |
| [ISoftEdge](./isoftedge) | Rappresenta un effetto Soft Edge. I bordi della forma sono sfocati, mentre il riempimento non è influenzato. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Oggetto immutabile che rappresenta un effetto soft edge. I bordi della forma sono sfocati, mentre il riempimento non è influenzato. |
| [ITint](./itint) | Rappresenta un effetto Tint. Sposta i valori colore dell'effetto verso/lontano dalla tonalità di un ammontare specificato. |
| [ITintEffectiveData](./itinteffectivedata) | Oggetto immutabile che rappresenta un effetto Tint. Sposta i valori colore dell'effetto verso/lontano dalla tonalità di un ammontare specificato. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->