---
title: IPictureFillFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een afbeeldingvullingsstijl voor.
type: docs
weight: 3225
url: /nl/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat klasse


Stelt een afbeeldingvulling-stijl voor.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Verwijder bijgesneden gebieden van de opvulling [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking voor dubbele waarden waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Retourneert het aantal procenten van de werkelijke afbeeldingshoogte dat onderaan de afbeelding wordt bijgesneden. Lezen **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Retourneert het aantal procenten van de werkelijke afbeeldingsbreedte dat aan de linkerkant van de afbeelding wordt bijgesneden. Lezen **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Retourneert het aantal procenten van de werkelijke afbeeldingsbreedte dat aan de rechterkant van de afbeelding wordt bijgesneden. Lezen **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Retourneert het aantal procenten van de werkelijke afbeeldingshoogte dat aan de bovenkant van de afbeelding wordt bijgesneden. Lezen **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Retourneert de dpi die wordt gebruikt om een afbeelding te vullen. Lezen **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Retourneert de afbeelding. Alleen-lezen [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Retourneert de invulmodus van de afbeelding. Lezen [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Retourneert de onderkant van het opvulrechthoek dat wordt gedefinieerd door een procentuele offset vanaf de onderkant van de begrenzingsbox van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Lezen **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Retourneert de linkerkant van het opvulrechthoek dat wordt gedefinieerd door een procentuele offset vanaf de linkerkant van de begrenzingsbox van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Lezen **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Retourneert de rechterkant van het opvulrechthoek dat wordt gedefinieerd door een procentuele offset vanaf de rechterkant van de begrenzingsbox van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Lezen **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Retourneert de bovenkant van het opvulrechthoek dat wordt gedefinieerd door een procentuele offset vanaf de bovenkant van de begrenzingsbox van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Lezen **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Retourneert hoe de textuur binnen de vorm is uitgelijnd. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het over de vorm wordt herhaald. Lezen [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Draait het textuurpatroon om zijn horizontale, verticale of beide assen. Lezen [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Retourneert de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten. Een positieve waarde verplaatst de textuur naar rechts, terwijl een negatieve waarde deze naar links verplaatst. Lezen **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Retourneert de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten. Een positieve waarde verplaatst de textuur naar beneden, terwijl een negatieve waarde deze naar boven verplaatst. Lezen **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Retourneert de horizontale schaal voor de textuurinvulling als percentage. Lezen **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Retourneert de verticale schaal voor de textuurinvulling als percentage. Lezen **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het C# lock()-statement voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets werkelijk, initialiseert enkel een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets werkelijk, initialiseert enkel een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object referentieel met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Stelt het aantal procenten van de werkelijke afbeeldingshoogte in dat onderaan de afbeelding wordt bijgesneden. Schrijven **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Stelt het aantal procenten van de werkelijke afbeeldingsbreedte in dat aan de linkerkant van de afbeelding wordt bijgesneden. Schrijven **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Stelt het aantal procenten van de werkelijke afbeeldingsbreedte in dat aan de rechterkant van de afbeelding wordt bijgesneden. Schrijven **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Stelt het aantal procenten van de werkelijke afbeeldingshoogte in dat aan de bovenkant van de afbeelding wordt bijgesneden. Schrijven **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Stelt de dpi in die wordt gebruikt om een afbeelding te vullen. Schrijven **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Stelt de invulmodus van de afbeelding in. Schrijven [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Stelt de onderkant van het opvulrechthoek in dat wordt gedefinieerd door een procentuele offset vanaf de onderkant van de begrenzingsbox van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Schrijven **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Stelt de linkerkant van het opvulrechthoek in dat wordt gedefinieerd door een procentuele offset vanaf de linkerkant van de begrenzingsbox van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Schrijven **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Stelt de rechterkant van het opvulrechthoek in dat wordt gedefinieerd door een procentuele offset vanaf de rechterkant van de begrenzingsbox van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Schrijven **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Stelt de bovenkant van het opvulrechthoek in dat wordt gedefinieerd door een procentuele offset vanaf de bovenkant van de begrenzingsbox van de vorm. Een positief percentage geeft een insnijding aan, terwijl een negatief percentage een uitsnijding aangeeft. Schrijven **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Stelt in hoe de textuur binnen de vorm wordt uitgelijnd. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het over de vorm wordt herhaald. Schrijven [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Draait het textuurpatroon om zijn horizontale, verticale of beide assen. Schrijven [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Stelt de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar rechts, terwijl een negatieve waarde deze naar links verplaatst. Schrijven **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Stelt de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar beneden, terwijl een negatieve waarde deze naar boven verplaatst. Schrijven **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Stelt de horizontale schaal voor de textuurinvulling in als percentage. Schrijven **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Stelt de verticale schaal voor de textuurinvulling in als percentage. Schrijven **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het omzetten van aangepaste objecten naar een string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het C# lock()-statement voor ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IFillParamSource](../ifillparamsource/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)