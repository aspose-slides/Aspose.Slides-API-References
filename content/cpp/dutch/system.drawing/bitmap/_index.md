---
title: Bitmap
second_title: "Aspose.Slides voor C++ API-referentie"
description: "Stelt een GDI+ bitmap-afbeelding voor. Objecten van deze klasse mogen alleen worden toegewezen met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 1
url: /nl/system.drawing/bitmap/
---
## Bitmap klasse


Stelt een GDI+ bitmap-afbeelding voor. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met de operator new, omdat dit resulteert in runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument door te geven aan functies.

```cpp
class Bitmap : public System::Drawing::Image
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Schakelt de pixelverwerkingsmodus in. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Construeert een nieuw [Bitmap](./) object van de opgegeven bestaande afbeelding. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Construeert een nieuw [Bitmap](./) object van de opgegeven stream. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Construeert een nieuw [Bitmap](./) object van het opgegeven bestand. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Construeert een nieuw [Bitmap](./) object van het opgegeven bestand. |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Construeert een nieuw [Bitmap](./) object dat een bitmap-afbeelding voorstelt met de opgegeven breedte, hoogte, pixelindeling en pixelgegevens. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Construeert een nieuw [Bitmap](./) object van de opgegeven bestaande afbeelding, geschaald naar de opgegeven grootte. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Construeert een nieuw [Bitmap](./) object van de opgegeven bestaande afbeelding met breedte en hoogte geschaald naar de opgegeven waarden. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Maakt een kopie van het huidige object. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Maakt een [Bitmap](./) object dat een kopie van een regio van de bitmap-afbeelding vertegenwoordigt die door het huidige object wordt voorgesteld. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Maakt een [Bitmap](./) object dat een kopie van een regio van de bitmap-afbeelding vertegenwoordigt die door het huidige object wordt voorgesteld. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Berekent de SHA1-hashwaarde. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Maakt een kopie van de opgegeven bitmap-afbeelding met pixelindeling gewijzigd naar Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | Vrijgeeft alle door het huidige object verworven bronnen. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Schakelt de pixelverwerkingsmodus uit. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN’s als gelijk beschouwd worden, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallen vergelijking waarbij twee NaN’s als gelijk beschouwd worden, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Maakt een [Image](../image/) object van het opgegeven bestand. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Construeert een [Bitmap](./) object van de opgegeven GDI-bitmap. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Maakt een [Image](../image/) object van de opgegeven stream. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Geeft een bit-gewijze combinaties van ImageFlags-enumwaarden die de attributen van de afbeelding weergeven. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Geeft een array van GUID’s die de afmetingen van frames binnen de afbeelding die door het huidige object wordt voorgesteld, weergeven. |
| int [get_Height](./get_height/)() const override | Geeft de hoogte van de afbeelding in pixels terug. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Geeft de horizontale resolutie van de afbeelding die door het huidige object wordt voorgesteld terug in pixels per inch. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Geeft het kleurenpalet terug dat door de afbeelding die door het huidige object wordt voorgesteld, wordt gebruikt. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Geeft de pixelindeling terug van de afbeelding die door het huidige object wordt voorgesteld. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Haalt de ID’s op van de eigenschapselementen die in deze afbeelding zijn opgeslagen. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Haalt alle eigenschapselementen (metadata-onderdelen) op die in deze afbeelding zijn opgeslagen. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Geeft het bestandsformaat terug van de afbeelding die door het huidige object wordt voorgesteld. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Geeft een [Size](../size/) object terug dat de breedte en hoogte van de afbeelding in pixels weergeeft. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Haalt een object op dat aanvullende gegevens over de afbeelding levert. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Geeft de verticale resolutie van de afbeelding die door het huidige object wordt voorgesteld terug in pixels per inch. |
| int [get_Width](./get_width/)() const override | Geeft de breedte van de afbeelding in pixels terug. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Geeft de grenzen van de afbeelding terug in de opgegeven meeteenheden. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Geeft het aantal frames van de opgegeven frame-dimensie terug. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt het hashen van aangepaste objecten in. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Maakt een GDI-bitmap-object van de bitmap die door het huidige object wordt voorgesteld. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Geeft de kleur van de opgegeven pixel terug. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Geeft het aantal bits terug dat wordt gebruikt om de kleurdiepte weer te geven in de opgegeven pixelindeling. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Geeft een ruwe pointer terug naar het onderliggende SkBitmap-object. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Haalt een miniatuur op voor dit [System::Drawing::Image](../image/) object. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het feitelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type dat door targetType wordt beschreven, vertegenwoordigt. Analoge van de C# ‘is’-operator. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Bepaalt of de opgegeven pixelindeling alfa-informatie bevat. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Geeft terug of het oorspronkelijke formaat een multi-image is. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Vergrendelt een [Bitmap](./) in het systeem-geheugen. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Vergrendelt een [Bitmap](./) in het systeem-geheugen. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Verandert de kleur van alle pixels met de opgegeven kleur naar transparant. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt het klonen van aangepaste types in. |
| [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| void [PremultipleColors](./premultiplecolors/)() | Premultipliseert de kleuren van de pixels van de afbeelding die door het huidige object wordt voorgesteld. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Roteert de afbeelding met een veelvoud van 90 graden en spiegelt deze. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Slaat de afbeelding die door het huidige object wordt voorgesteld op in het opgegeven bestand in PNG-formaat. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Slaat de afbeelding die door het huidige object wordt voorgesteld op in het opgegeven bestand in het opgegeven formaat. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Slaat de afbeelding die door het huidige object wordt voorgesteld op in de opgegeven stream in het opgegeven formaat. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Slaat de afbeelding die door het huidige object wordt voorgesteld op in het opgegeven bestand met de opgegeven encoder en encoder-parameters. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Slaat de afbeelding die door het huidige object wordt voorgesteld op in de opgegeven stream met de opgegeven encoder en encoder-parameters. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Voegt een frame toe aan het bestand of de stream die in een eerdere aanroep van de [Save()](../image/save/)-methode is opgegeven. |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Voegt een frame toe aan het bestand of de stream die in een eerdere aanroep van de [Save()](../image/save/)-methode is opgegeven. |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Selecteert het opgegeven frame. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Stelt het kleurenpalet in dat wordt gebruikt door de afbeelding die door het huidige object wordt voorgesteld. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Stelt een object in dat aanvullende gegevens over de afbeelding levert. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Stelt de kleur in van de opgegeven pixel in de bitmap-afbeelding die door het huidige object wordt voorgesteld. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Stelt de resolutie van de afbeelding in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-template-argument in op een zwakke pointer (in plaats van gedeelde). Stelt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en geeft de gedeelde referentieteller terug. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt het converteren van aangepaste objecten naar een string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Ontgrendelt de opgegeven bitmap uit het systeem-geheugen. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Image](../image/)
* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)