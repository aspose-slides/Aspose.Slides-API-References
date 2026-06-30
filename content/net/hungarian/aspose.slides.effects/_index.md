---
title: Aspose.Slides.Effects
second_title: Aspose.Sildes .NET API referencia
description: Osztályokat tartalmaz a Microsoft PowerPoint prezentációkban különféle hatásokkal való munkához.
type: docs
weight: 60
url: /hu/aspose.slides.effects/
---
Különféle hatásokkal való munka érdekében Microsoft PowerPoint prezentációkban használható osztályokat tartalmaz.

## Osztályok

| Osztály | Leírás |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Alpha kétfokozatú (Bi-Level) hatást ábrázol. Az Alpha (Áttetszőség) értékek, amelyek kisebbek a küszöbértéknél, 0-ra (teljesen átlátszó) módosulnak, a küszöbértéknél nagyobb vagy egyenlő Alpha értékek pedig 100%-ra (teljesen átlátszatlan) változnak. |
| [AlphaCeiling](./alphaceiling) | Alpha felső határt (Ceiling) ábrázol. Az Alpha (áttetszőség) értékek, amelyek nagyobbak, mint nulla, 100%-ra változnak. Más szóval, minden részben áttetsző teljesen áttetszatlanná válik. |
| [AlphaFloor](./alphafloor) | Alpha alsó határt (Floor) ábrázol. Az Alpha (áttetszőség) értékek, amelyek kisebbek, mint 100%, nullára módosulnak. Más szóval, minden részben átlátszó teljesen átlátszóvá válik. |
| [AlphaInverse](./alphainverse) | Alpha invertáló (Inverse) hatást ábrázol. Az Alpha (áttetszőség) értékek 100%-ból való kivonással invertálódnak. |
| [AlphaModulate](./alphamodulate) | Alpha moduláló (Modulate) hatást ábrázol. A hatás Alpha (áttetszőség) értékei egy rögzített százalékkal szorozódnak. A hatáskonténer egy olyan hatást ad meg, amely Alpha értékeket tartalmaz a moduláláshoz. |
| [AlphaModulateFixed](./alphamodulatefixed) | Alpha fix moduláló (Modulate Fixed) hatást ábrázol. A hatás Alpha (áttetszőség) értékei egy rögzített százalékkal szorozódnak. |
| [AlphaReplace](./alphareplace) | Alpha helyettesítő (Replace) hatást ábrázol. A hatás Alpha (áttetszőség) értékei egy rögzített Alpha értékkel cserélődnek. |
| [BiLevel](./bilevel) | Kétfokozatú (Fekete/Fehér) hatást ábrázol. Azok a bemeneti színek, amelyek fényessége (luminance) kisebb a megadott küszöbértéknél, feketére változnak. A bemeneti színek, amelyek fényessége nagyobb vagy egyenlő a megadott értékkel, fehérre állítódnak. Az Alpha hatásértékek erre a hatásra nem változnak. |
| [Blur](./blur) | Elmosódás (Blur) hatást ábrázol, amely az egész alakzatra, a kitöltéssel együtt kerül alkalmazásra. Minden színcsatorna, beleértve az Alpha-t is, érintett. |
| [BrightnessContrast](./brightnesscontrast) | Fényerő/Kontraszt (BrightnessContrast) hatást ábrázol. Állítja a fényerőt és a kontrasztot. |
| [ColorChange](./colorchange) | Színcsere (Color Change) hatást ábrázol. A FromColor példányai a ToColor példányaival cserélődnek. |
| [ColorReplace](./colorreplace) | Színhelyettesítés (Color Replacement) hatást ábrázol. Az összes hatásszín egy rögzített színre változik. Az Alpha értékek nem változnak. |
| [Duotone](./duotone) | Duotone hatást ábrázol. Minden képpontnál a Color1 és Color2 lineáris interpolációval kombinálódik, hogy meghatározza az új színt. |
| [EffectFactory](./effectfactory) | Lehetővé teszi hatások létrehozását |
| [FillOverlay](./filloverlay) | Kitöltés felülírás (Fill Overlay) hatást ábrázol. Egy kitöltés felülírásával további kitöltés adható egy objektumnak, és a két kitöltés összeolvasztható. |
| [Glow](./glow) | Ragyogás (Glow) hatást ábrázol, amelyben egy színű elmosódott körvonalat adunk az objektum széleihez. |
| [GrayScale](./grayscale) | Szürkeárnyalatos (Gray Scale) hatást ábrázol. Az összes hatásszínértéket egy szürke árnyalatra konvertálja, amely a fényességnek megfelelő. Az Alpha (áttetszőség) értékek nem változnak. |
| [HSL](./hsl) | Árnyalat/Telítettség/Fényesség (Hue/Saturation/Luminance) hatást ábrázol. Az árnyalat, a telítettség és a fényesség mindegyike a jelenlegi értékhez képest állítható. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Előállíthatatlan objektum, amely egy csak olvasható (readonly) gyűjteményt ábrázol a hatékony képtranszformációs hatásokról. |
| [ImageTransformOperation](./imagetransformoperation) | Absztrakt képtranszformációs hatást ábrázol. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Képre alkalmazott hatások gyűjteményét ábrázol. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Lehetővé teszi képtranszformációs műveletek létrehozását |
| [InnerShadow](./innershadow) | Belső árnyék (Inner Shadow) hatást ábrázol. |
| [Luminance](./luminance) | Fényesség (Luminance) hatást ábrázol. A fényerő lineárisan a színeket fehérhez vagy fekete felé tolja. A kontraszt minden színt közelebb vagy távolabb helyez. |
| [OuterShadow](./outershadow) | Külső árnyék (Outer Shadow) hatást ábrázol. |
| [PresetShadow](./presetshadow) | Előre beállított árnyék (Preset Shadow) hatást ábrázol. |
| [Reflection](./reflection) | Tükröződés (Reflection) hatást ábrázol. |
| [SoftEdge](./softedge) | Lágy él (Soft Edge) hatást ábrázol. Az alakzat szélei elmosódnak, míg a kitöltés érintetlen marad. |
| [Tint](./tint) | Árnyalatás (Tint) hatást ábrázol. A hatásszínértékeket a megadott mennyiséggel a szín felé vagy elől tolja. |

## Interfészek

| Interfész | Leírás |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Alpha kétfokozatú (Bi-Level) hatást ábrázol. Az Alpha (Áttetszőség) értékek, amelyek kisebbek a küszöbértéknél, 0-ra (teljesen átlátszó) módosulnak, a küszöbértéknél nagyobb vagy egyenlő Alpha értékek pedig 100%-ra (teljesen átlátszatlan) változnak. |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Előállíthatatlan objektum, amely egy Alpha kétfokozatú (Bi-Level) hatást ábrázol. Az Alpha (Áttetszőség) értékek, amelyek kisebbek a küszöbértéknél, 0-ra (teljesen átlátszó) módosulnak, a küszöbértéknél nagyobb vagy egyenlő Alpha értékek pedig 100%-ra (teljesen átlátszatlan) változnak. |
| [IAlphaCeiling](./ialphaceiling) | Alpha felső határt (Ceiling) ábrázol. Az Alpha (áttetszőség) értékek, amelyek nagyobbak, mint nulla, 100%-ra változnak. Más szóval, minden részben áttetsző teljesen áttetszatlanná válik. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Előállíthatatlan objektum, amely egy Alpha felső határt (Ceiling) ábrázol. Az Alpha (áttetszőség) értékek, amelyek nagyobbak, mint nulla, 100%-ra változnak. Más szóval, minden részben áttetsző teljesen áttetszatlanná válik. |
| [IAlphaFloor](./ialphafloor) | Alpha alsó határt (Floor) ábrázol. Az Alpha (áttetszőség) értékek, amelyek kisebbek, mint 100%, nullára módosulnak. Más szóval, minden részben átlátszó teljesen átlátszóvá válik. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Előállíthatatlan objektum, amely egy Alpha alsó határt (Floor) ábrázol. Az Alpha (áttetszőség) értékek, amelyek kisebbek, mint 100%, nullára módosulnak. Más szóval, minden részben átlátszó teljesen átlátszóvá válik. |
| [IAlphaInverse](./ialphainverse) | Alpha invertáló (Inverse) hatást ábrázol. Az Alpha (áttetszőség) értékek 100%-ból való kivonással invertálódnak. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Előállíthatatlan objektum, amely egy Alpha invertáló (Inverse) hatást ábrázol. Az Alpha (áttetszőség) értékek 100%-ból való kivonással invertálódnak. |
| [IAlphaModulate](./ialphamodulate) | Alpha moduláló (Modulate) hatást ábrázol. A hatás Alpha (áttetszőség) értékei egy rögzített százalékkal szorozódnak. A hatáskonténer egy olyan hatást ad meg, amely Alpha értékeket tartalmaz a moduláláshoz. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Előállíthatatlan objektum, amely egy Alpha moduláló (Modulate) hatást ábrázol. A hatás Alpha (áttetszőség) értékei egy rögzített százalékkal szorozódnak. A hatáskonténer egy olyan hatást ad meg, amely Alpha értékeket tartalmaz a moduláláshoz. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Alpha fix moduláló (Modulate Fixed) hatást ábrázol. A hatás Alpha (áttetszőség) értékei egy rögzített százalékkal szorozódnak. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Előállíthatatlan objektum, amely egy Alpha fix moduláló (Modulate Fixed) hatást ábrázol. A hatás Alpha (áttetszőség) értékei egy rögzített százalékkal szorozódnak. |
| [IAlphaReplace](./ialphareplace) | Alap IImageTransformOperation interfész. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Előállíthatatlan objektum, amely egy Alpha helyettesítő (Replace) hatást ábrázol. A hatás Alpha (áttetszőség) értékei egy rögzített Alpha értékkel cserélődnek. |
| [IBiLevel](./ibilevel) | Alap IImageTransformOperation interfész. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Előállíthatatlan objektum, amely egy Kétfokozatú (Fekete/Fehér) hatást ábrázol. A bemeneti színek, amelyek fényessége (luminance) kisebb a megadott küszöbértéknél, feketére változnak. A bemeneti színek, amelyek fényessége nagyobb vagy egyenlő a megadott értékkel, fehérre állítódnak. Az Alpha hatásértékek erre a hatásra nem változnak. |
| [IBlur](./iblur) | Elmosódás (Blur) hatást ábrázol, amely az egész alakzatra, a kitöltéssel együtt kerül alkalmazásra. Minden színcsatorna, beleértve az Alpha-t is, érintett. |
| [IBlurEffectiveData](./iblureffectivedata) | Előállíthatatlan objektum, amely elmosódás (Blur) hatást ábrázol, amely az egész alakzatra, a kitöltéssel együtt kerül alkalmazásra. Minden színcsatorna, beleértve az Alpha-t is, érintett. |
| [IBrightnessContrast](./ibrightnesscontrast) | Fényerő/Kontraszt (BrightnessContrast) hatást ábrázol. Állítja a fényerőt és a kontrasztot. |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | Előállíthatatlan objektum, amely Fényerő/Kontraszt (BrightnessContrast) hatást ábrázol. Állítja a fényerőt és a kontrasztot. |
| [IColorChange](./icolorchange) | Színcsere (Color Change) hatást ábrázol. A FromColor példányai a ToColor példányaival cserélődnek. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Előállíthatatlan objektum, amely Színcsere (Color Change) hatást ábrázol. A FromColor példányai a ToColor példányaival cserélődnek. |
| [IColorReplace](./icolorreplace) | Színhelyettesítés (Color Replacement) hatást ábrázol. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Előállíthatatlan objektum, amely Színhelyettesítés (Color Replacement) hatást ábrázol. Az összes hatásszín egy rögzített színre változik. Az Alpha értékek nem változnak. |
| [IDuotone](./iduotone) | Duotone hatást ábrázol. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Előállíthatatlan objektum, amely Duotone hatást ábrázol. Minden képpontnál a clr1 és clr2 lineáris interpolációval kombinálódik, hogy meghatározza az új színt. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Alap osztály előállíthatatlan objektumok számára, amelyek hatást képviselnek. |
| [IEffectFactory](./ieffectfactory) | Lehetővé teszi hatások példányainak létrehozását |
| [IFillOverlay](./ifilloverlay) | Kitöltés felülírás (Fill Overlay) hatást ábrázol. Egy kitöltés felülírásával további kitöltés adható egy objektumnak, és a két kitöltés összeolvasztható. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Előállíthatatlan objektum, amely Kitöltés felülírás (Fill Overlay) hatást ábrázol. Egy kitöltés felülírásával további kitöltés adható egy objektumnak, és a két kitöltés összeolvasztható. |
| [IGlow](./iglow) | Ragyogás (Glow) hatást ábrázol, amelyben egy színű elmosódott körvonalat adunk az objektum széleihez. |
| [IGlowEffectiveData](./igloweffectivedata) | Előállíthatatlan objektum, amely Ragyogás (Glow) hatást ábrázol, amelyben egy színű elmosódott körvonalat adunk az objektum széleihez. |
| [IGrayScale](./igrayscale) | IImageTransformOperation interfész. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Előállíthatatlan objektum, amely Szürkeárnyalatos (Gray Scale) hatást ábrázol. Az összes hatásszínértéket egy szürke árnyalatra konvertálja, amely a fényességnek megfelelő. Az Alpha (áttetszőség) értékek nem változnak. |
| [IHSL](./ihsl) | Árnyalat/Telítettség/Fényesség (Hue/Saturation/Luminance) hatást ábrázol. Az árnyalat, a telítettség és a fényesség mindegyike a jelenlegi értékhez képest állítható. |
| [IHSLEffectiveData](./ihsleffectivedata) | Árnyalat/Telítettség/Fényesség (Hue/Saturation/Luminance) hatást ábrázol. Az árnyalat, a telítettség és a fényesség mindegyike a jelenlegi értékhez képest állítható. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Előállíthatatlan objektum, amely egy csak olvasható (readonly) gyűjteményt ábrázol a hatékony képtranszformációs hatásokról. |
| [IImageTransformOperation](./iimagetransformoperation) | Absztrakt képtranszformációs hatást ábrázol. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Képre alkalmazott hatások gyűjteményét ábrázol. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Lehetővé teszi képtranszformációs hatások példányainak létrehozását |
| [IInnerShadow](./iinnershadow) | Belső árnyék (inner shadow) hatást ábrázol. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | Előállíthatatlan objektum, amely Belső árnyék (inner shadow) hatást ábrázol. |
| [ILuminance](./iluminance) | Fényesség (Luminance) hatást ábrázol. A fényerő lineárisan a színeket fehérhez vagy fekete felé tolja. A kontraszt minden színt közelebb vagy távolabb helyez. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Fényesség (Luminance) hatást ábrázol. A fényerő lineárisan a színeket fehérhez vagy fekete felé tolja. A kontraszt minden színt közelebb vagy távolabb helyez. |
| [IOuterShadow](./ioutershadow) | Külső árnyék (Outer Shadow) hatást ábrázol. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Előállíthatatlan objektum, amely Külső árnyék (Outer Shadow) hatást ábrázol. |
| [IPresetShadow](./ipresetshadow) | Előre beállított árnyék (Preset Shadow) hatást ábrázol. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Előállíthatatlan objektum, amely Előre beállított árnyék (Preset Shadow) hatást ábrázol. |
| [IReflection](./ireflection) | Tükröződés (reflection) hatást ábrázol. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Előállíthatatlan objektum, amely Tükröződés (reflection) hatást ábrázol. |
| [ISoftEdge](./isoftedge) | Lágy él (Soft Edge) hatást ábrázol. Az alakzat szélei elmosódnak, míg a kitöltés érintetlen marad. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Előállíthatatlan objektum, amely Lágy él (soft edge) hatást ábrázol. Az alakzat szélei elmosódnak, míg a kitöltés érintetlen marad. |
| [ITint](./itint) | Árnyalatás (Tint) hatást ábrázol. A hatásszínértékeket a megadott mennyiséggel a szín felé vagy elől tolja. |
| [ITintEffectiveData](./itinteffectivedata) | Előállíthatatlan objektum, amely Árnyalatás (Tint) hatást ábrázol. A hatásszínértékeket a megadott mennyiséggel a szín felé vagy elől tolja. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->