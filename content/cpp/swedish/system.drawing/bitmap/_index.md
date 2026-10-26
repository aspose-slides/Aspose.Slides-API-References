---
title: Bitmap
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en GDI+ bitmap-bild. Objekt av den här klassen bör endast allokeras med hjälp av System::MakeObject() funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid den här klassen i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 1
url: /sv/system.drawing/bitmap/
---
## Bitmap klass

Representerar en GDI+ bitmap-bild. Objekt av den här klassen bör bara allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att resultera i körfel och/eller påståendefel. Omslut alltid den här klassen i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Bitmap : public System::Drawing::Image
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Aktiverar pixelbearbetningsläge. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Skapar ett nytt [Bitmap](./)-objekt från den angivna befintliga bilden. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Skapar ett nytt [Bitmap](./)-objekt från den angivna strömmen. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Skapar ett nytt [Bitmap](./)-objekt från den angivna filen. |
| [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Skapar ett nytt [Bitmap](./)-objekt från den angivna filen. |
| [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Skapar ett nytt [Bitmap](./)-objekt som representerar en bitmap-bild med angiven bredd, höjd, pixelformat och pixeldatan. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Skapar ett nytt [Bitmap](./)-objekt från den angivna befintliga bilden, skalad till den angivna storleken. |
| [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Skapar ett nytt [Bitmap](./)-objekt från den angivna befintliga bilden med bredd och höjd skalade till de angivna värdena. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Skapar en kopia av det aktuella objektet. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Skapar ett [Bitmap](./)-objekt som representerar en kopia av ett område av bitmap-bilden som det aktuella objektet representerar. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Skapar ett [Bitmap](./)-objekt som representerar en kopia av ett område av bitmap-bilden som det aktuella objektet representerar. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Beräknar SHA1-hashvärdet. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Skapar en kopia av den angivna bitmap-bilden med pixelformat ändrat till Format32bppArgb. |
| void [Dispose](../image/dispose/)() override | Frigör alla resurser som det aktuella objektet har förvärvat. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Inaktiverar pixelbearbetningsläge. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Skapar ett [Image](../image/)-objekt från den angivna filen. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Skapar ett [Bitmap](./)-objekt från den angivna GDI-bitmapen. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Skapar ett [Image](../image/)-objekt från den angivna strömmen. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Returnerar en bitvis kombination av ImageFlags-enummervärden som representerar bildens attribut. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Returnerar en array av GUID:er som representerar dimensionerna för ramar i bilden som det aktuella objektet representerar. |
| int [get_Height](./get_height/)() const override | Returnerar bildens höjd i pixlar. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Returnerar den horisontella upplösningen för bilden som det aktuella objektet representerar i pixlar per tum. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Returnerar färgpaletten som används av bilden som det aktuella objektet representerar. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Returnerar pixelformatet för bilden som det aktuella objektet representerar. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Hämtar ID:n för de egenskapsobjekt som lagras i denna bild. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Hämtar alla egenskapsobjekt (metadata) som lagras i denna bild. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Returnerar filformatet för bilden som det aktuella objektet representerar. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Returnerar ett [Size](../size/)-objekt som representerar bildens bredd och höjd i pixlar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Hämtar ett objekt som tillhandahåller ytterligare data om bilden. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Returnerar den vertikala upplösningen för bilden som det aktuella objektet representerar i pixlar per tum. |
| int [get_Width](./get_width/)() const override | Returnerar bildens bredd i pixlar. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Returnerar bildens gränser i de angivna måttenheterna. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Returnerar antalet ramar för den angivna ramar-dimensionen. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Skapar ett GDI-bitmap-objekt från bitmap-bilden som det aktuella objektet representerar. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Returnerar färgen på den angivna pixeln. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Returnerar antalet bitar som används för att representera färgdjupet i det angivna pixelformatet. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Returnerar en råpekare till det underliggande SkBitmap-objektet. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Hämtar en miniatyr för detta [System::Drawing::Image](../image/)-objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Avgör om det angivna pixelformatet innehåller alfa-information. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Returnerar om det ursprungliga formatet är en multi-bild. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Låser en [Bitmap](./) i systemminnet. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Låser en [Bitmap](./) i systemminnet. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Ändrar färgen på alla pixlar med den angivna färgen till transparent. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| void [PremultipleColors](./premultiplecolors/)() | Premultiplicerar färgerna på pixlarna i bilden som det aktuella objektet representerar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför ett värdetyp-objekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med det angivna värdet. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Rotera bilden till en multipel av 90 grader och vänd. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Sparar bilden som det aktuella objektet representerar till den angivna filen i PNG-format. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Sparar bilden som det aktuella objektet representerar till den angivna filen i det angivna formatet. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Sparar bilden som det aktuella objektet representerar till den angivna strömmen i det angivna formatet. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Sparar bilden som det aktuella objektet representerar till den angivna filen med den angivna kodaren och kodarparametrar. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Sparar bilden som det aktuella objektet representerar till den angivna strömmen med den angivna kodaren och kodarparametrar. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Lägger till en ram till filen eller strömmen som specificerats i ett tidigare anrop av [Save()](../image/save/)-metoden. |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Lägger till en ram till filen eller strömmen som specificerats i ett tidigare anrop av [Save()](../image/save/)-metoden. |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Väljer den angivna ramen. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Ställer in färgpaletten som används av bilden som det aktuella objektet representerar. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Ställer in ett objekt som tillhandahåller ytterligare data om bilden. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Ställer in färgen på den angivna pixeln i bitmap-bilden som det aktuella objektet representerar. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Ställer in upplösningen för bilden. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te mallargument till en svag pekare (istället för delad). Tillåter att byta ut pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delat referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar det delade referensräknaren. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar det delade referensräknaren. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Låser upp den angivna bitmapen från systemminnet. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [Image](../image/)
* Namnrymd [System::Drawing](../)
* Bibliotek [Aspose.Slides](../../)