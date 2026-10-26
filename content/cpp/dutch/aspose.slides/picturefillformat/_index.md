---
title: PictureFillFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een afbeeldingvulstijl voor.
type: docs
weight: 4720
url: /nl/aspose.slides/picturefillformat/
---
## PictureFillFormat klasse

Stelt een afbeeldingvulstijl voor.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Comprimeert de afbeelding door de grootte te verkleinen op basis van de vormgrootte en de opgegeven resolutie. Optioneel verwijdert het ook bijgesneden gebieden. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Verwijdert bijgesneden gebieden van de vulling [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergelijkt met opgegeven object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Retourneert het aantal procenten van de werkelijke afbeeldingshoogte dat van de onderkant van de afbeelding wordt bijgesneden. Lezen **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Retourneert het aantal procenten van de werkelijke afbeeldingsbreedte dat van de linkerkant van de afbeelding wordt bijgesneden. Lezen **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Retourneert het aantal procenten van de werkelijke afbeeldingsbreedte dat van de rechterkant van de afbeelding wordt bijgesneden. Lezen **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Retourneert het aantal procenten van de werkelijke afbeeldingshoogte dat van de bovenkant van de afbeelding wordt bijgesneden. Lezen **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Retourneert de dpi die wordt gebruikt om een afbeelding te vullen. Lezen **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate object. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retourneert ouder [IPresentationComponent](../ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Retourneert de afbeelding. Alleen-lezen [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Retourneert de afbeeldingsvulmodus. Lezen [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Retourneert de onderrand van de vulrechthoek die wordt gedefinieerd door een procentuele offset vanaf de onderrand van de begrenzingsbox van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Retourneert de linkerrand van de vulrechthoek die wordt gedefinieerd door een procentuele offset vanaf de linkerrand van de begrenzingsbox van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Retourneert de rechterrand van de vulrechthoek die wordt gedefinieerd door een procentuele offset vanaf de rechterrand van de begrenzingsbox van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Retourneert de boverrand van de vulrechthoek die wordt gedefinieerd door een procentuele offset vanaf de boverrand van de begrenzingsbox van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Lezen **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Retourneert hoe de textuur binnen de vorm is uitgelijnd. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich over de vorm herhaalt. Lezen [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Draait de textuurtegels om hun horizontale, verticale of beide assen. Lezen [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Retourneert de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten. Een positieve waarde verplaatst de textuur naar rechts, een negatieve waarde naar links. Lezen **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Retourneert de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten. Een positieve waarde verplaatst de textuur naar beneden, een negatieve waarde naar boven. Lezen **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Retourneert de horizontale schaal voor de textuurvulling als een percentage. Lezen **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Retourneert de verticale schaal voor de textuurvulling als een percentage. Lezen **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de gegevensstructuur van de referentieteller op die aan het object is gekoppeld. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retourneert hashcode. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haal het daadwerkelijke type van het object op. Analogie van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analogie van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, initialiseert enkel een nieuw object en maakt het mogelijk kopiëren van subklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert enkel een nieuw object en maakt het mogelijk kopiëren van subklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Stelt het aantal procenten van de werkelijke afbeeldingshoogte in dat van de onderkant van de afbeelding wordt bijgesneden. Schrijf **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Stelt het aantal procenten van de werkelijke afbeeldingsbreedte in dat van de linkerkant van de afbeelding wordt bijgesneden. Schrijf **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Stelt het aantal procenten van de werkelijke afbeeldingsbreedte in dat van de rechterkant van de afbeelding wordt bijgesneden. Schrijf **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Stelt het aantal procenten van de werkelijke afbeeldingshoogte in dat van de bovenkant van de afbeelding wordt bijgesneden. Schrijf **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Stelt de dpi in die wordt gebruikt om een afbeelding te vullen. Schrijf **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Stelt de afbeeldingvulmodus in. Schrijf [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Stelt de onderrand van de vulrechthoek in die wordt gedefinieerd door een procentuele offset vanaf de onderrand van de begrenzingsbox van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Schrijf **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Stelt de linkerrand van de vulrechthoek in die wordt gedefinieerd door een procentuele offset vanaf de linkerrand van de begrenzingsbox van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Schrijf **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Stelt de rechterrand van de vulrechthoek in die wordt gedefinieerd door een procentuele offset vanaf de rechterrand van de begrenzingsbox van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Schrijf **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Stelt de boverrand van de vulrechthoek in die wordt gedefinieerd door een procentuele offset vanaf de boverrand van de begrenzingsbox van de vorm. Een positief percentage geeft een inset aan, terwijl een negatief percentage een outset aangeeft. Schrijf **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Stelt in hoe de textuur binnen de vorm is uitgelijnd. Deze instelling bepaalt het startpunt van het textuurpatroon en hoe het zich over de vorm herhaalt. Schrijf [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Draait de textuurtegels om hun horizontale, verticale of beide assen. Schrijf [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Stelt de horizontale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar rechts, een negatieve waarde naar links. Schrijf **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Stelt de verticale offset van de textuur ten opzichte van de oorsprong van de vorm in punten in. Een positieve waarde verplaatst de textuur naar beneden, een negatieve waarde naar boven. Schrijf **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Stelt de horizontale schaal voor de textuurvulling in als een percentage. Schrijf **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Stelt de verticale schaal voor de textuurvulling in als een percentage. Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Stelt toe om pointers in containers te wisselen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het mogelijk aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [PVIObject](../pviobject/)
* Klasse [IPictureFillFormat](../ipicturefillformat/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)