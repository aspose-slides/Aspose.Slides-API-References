---
title: IPictureFillFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar en bildfyllningsstil.
type: docs
weight: 3225
url: /sv/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat klass


Representerar en bildfyllningsstil.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. Valfritt raderar den också beskurna områden. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Komprimerar bilden genom att minska dess storlek baserat på figurens storlek och angiven upplösning. Valfritt raderar den också beskurna områden. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Raderar beskurna områden av fyllningen [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil floating-point-jämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil floating-point-jämförelse där två NaN-värden anses lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Returnerar antalet procent av den verkliga bildhöjden som beskärs från bildens nederkant. Läs **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Returnerar antalet procent av den verkliga bildbredden som beskärs från bildens vänstra kant. Läs **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Returnerar antalet procent av den verkliga bildbredden som beskärs från bildens högra kant. Läs **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Returnerar antalet procent av den verkliga bildhöjden som beskärs från bildens överkant. Läs **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Returnerar dpi som används för att fylla en bild. Läs **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Returnerar bilden. Skrivskyddad [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Returnerar bildfyllnadsläget. Läs [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Returnerar den nedre kanten av fyllningsrektangeln som definieras av en procentuell offset från den nedre kanten av figurens omgivningsruta. En positiv procent specificerar en inskjutning, medan en negativ procent specificerar en utskjutning. Läs **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Returnerar den vänstra kanten av fyllningsrektangeln som definieras av en procentuell offset från den vänstra kanten av figurens omgivningsruta. En positiv procent specificerar en inskjutning, medan en negativ procent specificerar en utskjutning. Läs **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Returnerar den högra kanten av fyllningsrektangeln som definieras av en procentuell offset från den högra kanten av figurens omgivningsruta. En positiv procent specificerar en inskjutning, medan en negativ procent specificerar en utskjutning. Läs **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Returnerar den övre kanten av fyllningsrektangeln som definieras av en procentuell offset från den övre kanten av figurens omgivningsruta. En positiv procent specificerar en inskjutning, medan en negativ procent specificerar en utskjutning. Läs **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Returnerar hur texturen är justerad inom figuren. Denna inställning styr startpunkten för texturmönstret och hur det repeteras över figuren. Läs [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Vänder texturstapeln kring dess horisontella, vertikala eller båda axlar. Läs [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Returnerar den horisontella offseten för texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen åt höger, ett negativt värde flyttar den åt vänster. Läs **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Returnerar den vertikala offseten för texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, ett negativt värde flyttar den uppåt. Läs **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Returnerar den horisontella skalan för texturfyllning som procent. Läs **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Returnerar den vertikala skalan för texturfyllning som procent. Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är kopplad till objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Ställer in antalet procent av den verkliga bildhöjden som beskärs från bildens nederkant. Skriv **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Ställer in antalet procent av den verkliga bildbredden som beskärs från bildens vänstra kant. Skriv **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Ställer in antalet procent av den verkliga bildbredden som beskärs från bildens högra kant. Skriv **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Ställer in antalet procent av den verkliga bildhöjden som beskärs från bildens överkant. Skriv **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Ställer in dpi som används för att fylla en bild. Skriv **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Ställer in bildfyllnadsläget. Skriv [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Ställer in den nedre kanten av fyllningsrektangeln som definieras av en procentuell offset från den nedre kanten av figurens omgivningsruta. En positiv procent specificerar en inskjutning, medan en negativ procent specificerar en utskjutning. Skriv **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Ställer in den vänstra kanten av fyllningsrektangeln som definieras av en procentuell offset från den vänstra kanten av figurens omgivningsruta. En positiv procent specificerar en inskjutning, medan en negativ procent specificerar en utskjutning. Skriv **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Ställer in den högra kanten av fyllningsrektangeln som definieras av en procentuell offset från den högra kanten av figurens omgivningsruta. En positiv procent specificerar en inskjutning, medan en negativ procent specificerar en utskjutning. Skriv **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Ställer in den övre kanten av fyllningsrektangeln som definieras av en procentuell offset från den övre kanten av figurens omgivningsruta. En positiv procent specificerar en inskjutning, medan en negativ procent specificerar en utskjutning. Skriv **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Ställer in hur texturen är justerad inom figuren. Denna inställning styr startpunkten för texturmönstret och hur det repeteras över figuren. Skriv [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Vänder texturstapeln kring dess horisontella, vertikala eller båda axlar. Skriv [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Ställer in den horisontella offseten för texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen åt höger, ett negativt värde flyttar den åt vänster. Skriv **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Ställer in den vertikala offseten för texturen från figurens ursprung i punkter. Ett positivt värde flyttar texturen nedåt, ett negativt värde flyttar den uppåt. Skriv **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Ställer in den horisontella skalan för texturfyllning som procent. Skriv **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Ställer in den vertikala skalan för texturfyllning som procent. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'th templat-argument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klass [IFillParamSource](../ifillparamsource/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)