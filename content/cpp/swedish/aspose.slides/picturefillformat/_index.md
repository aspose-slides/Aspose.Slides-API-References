---
title: PictureFillFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar en bildfyllningsstil.
type: docs
weight: 4720
url: /sv/aspose.slides/picturefillformat/
---
## PictureFillFormat klass

Representerar en bildfyllningsstil.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt tar den även bort beskurna områden. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Komprimerar bilden genom att minska dess storlek baserat på formens storlek och angiven upplösning. Eventuellt tar den även bort beskurna områden. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Ta bort beskurna områden i fyllningen [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Jämför med angivet objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar jämförelse av flyttal i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Returnerar antalet procent av den verkliga bildhöjden som beskärs från bildens botten. Läs **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Returnerar antalet procent av den verkliga bildbredden som beskärs från bildens vänstra sida. Läs **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Returnerar antalet procent av den verkliga bildbredden som beskärs från bildens högra sida. Läs **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Returnerar antalet procent av den verkliga bildhöjden som beskärs från bildens topp. Läs **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Returnerar dpi som används för att fylla en bild. Läs **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returnerar Parent_Immediate-objekt. Skrivskyddad [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Returnerar bilden. Skrivskyddad [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Returnerar bildfyllningsläget. Läs [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Returnerar nedre kant av fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns nedre kant i formens omgivningsruta. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Läs **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Returnerar vänsterkant av fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns vänstra kant i formens omgivningsruta. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Läs **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Returnerar högra kanten av fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns högra kant i formens omgivningsruta. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Läs **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Returnerar övre kanten av fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns övre kant i formens omgivningsruta. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Läs **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Returnerar hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Läs [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Vänder texturplattan kring dess horisontella, vertikala eller båda axlar. Läs [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Returnerar horisontell förskjutning av texturen från formens ursprung i punkter. Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster. Läs **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Returnerar vertikal förskjutning av texturen från formens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Läs **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Returnerar horisontell skala för texturfyllning i procent. Läs **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Returnerar vertikal skala för texturfyllning i procent. Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är kopplad till objektet. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returnerar hash-kod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens av värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Ställer in antalet procent av den verkliga bildhöjden som beskärs från bildens botten. Skriv **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Ställer in antalet procent av den verkliga bildbredden som beskärs från bildens vänstra sida. Skriv **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Ställer in antalet procent av den verkliga bildbredden som beskärs från bildens högra sida. Skriv **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Ställer in antalet procent av den verkliga bildhöjden som beskärs från bildens topp. Skriv **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Ställer in dpi som används för att fylla en bild. Skriv **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Ställer in bildfyllningsläget. Skriv [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Ställer in nedre kanten av fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns nedre kant i formens omgivningsruta. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Skriv **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Ställer in vänsterkant av fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns vänstra kant i formens omgivningsruta. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Skriv **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Ställer in högra kanten av fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns högra kant i formens omgivningsruta. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Skriv **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Ställer in övre kanten av fyllningsrektangeln som definieras av en procentuell förskjutning från rektangelns övre kant i formens omgivningsruta. En positiv procent anger en inskjutning, medan en negativ procent anger en utskjutning. Skriv **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Ställer in hur texturen är justerad inom formen. Denna inställning styr startpunkten för texturmönstret och hur det upprepas över formen. Skriv [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Vänder texturplattan kring dess horisontella, vertikala eller båda axlar. Skriv [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Ställer in horisontell förskjutning av texturen från formens ursprung i punkter. Ett positivt värde flyttar texturen åt höger, medan ett negativt värde flyttar den åt vänster. Skriv **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Ställer in vertikal förskjutning av texturen från formens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, medan ett negativt värde flyttar den uppåt. Skriv **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Ställer in horisontell skala för texturfyllning i procent. Skriv **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Ställer in vertikal skala för texturfyllning i procent. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n:te mallargumentet till en svag pekare (i stället för delad). Gör det möjligt att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning enligt C# lock()-sats för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigir alla interna datastrukturer. |

## Se även

* Klass [PVIObject](../pviobject/)
* Klass [IPictureFillFormat](../ipicturefillformat/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)