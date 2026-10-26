---
title: TiffOptions
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.
type: docs
weight: 768
url: /sv/aspose.slides.export/tiffoptions/
---
## TiffOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i TIFF-format.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | Specificerar algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ kommer endast att tillämpas om [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) är inställt på [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) eller [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) Läs [BlackWhiteConversionMode](../blackwhiteconversionmode/). Standard är [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | Specificerar kompressionstypen. Läs [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Returnerar typsnitt som används om källtypsnittet inte hittas. Läs [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | Specificerar horisontell upplösning i punkter per tum. Läs **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | Specificerar vertikal upplösning i punkter per tum. Läs **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Returnerar den visuella stilen för gradienten. Läs [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | Specificerar storleken på en genererad TIFF-bild. Standardvärdet är 0x0, vilket innebär att bildstorlekarna beräknas baserat på presentationsbildens storlek. Läs [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Tillhandahåller alternativ som styr utseendet på [Ink](../../aspose.slides.ink/)-objekt i exporterade dokument. Skrivskyddad [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | Specificerar pixelformatet för de genererade bilderna. Läs [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Specificerar om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Specificerar om hyperlänkar med JavaScript-anrop ska hoppas över vid sparning av presentationen. Läs **bool**. Standardvärdet är **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Hämtar läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Returnerar eller ställer in ett objekt som tar emot varningar och beslutar om laddningsprocessen ska fortsätta eller avbrytas. Läs [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning med C#-statement lock(). Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt per referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetyp-objekt per referens med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | Specificerar algoritmen för att konvertera en färgbild till en svartvit bild. Detta alternativ kommer endast att tillämpas om [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) är inställt på [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) eller [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) Skriv [BlackWhiteConversionMode](../blackwhiteconversionmode/). Standard är [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | Specificerar kompressionstypen. Skriv [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ställer in typsnittet som används om källtypsnittet inte hittas. Skriver [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | Specificerar horisontell upplösning i punkter per tum. Skriv **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | Specificerar vertikal upplösning i punkter per tum. Skriv **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ställer in den visuella stilen för gradienten. Skriver [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Specificerar storleken på en genererad TIFF-bild. Standardvärdet är 0x0, vilket innebär att bildstorlekarna beräknas baserat på presentationsbildens storlek. Skriver [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | Specificerar pixelformatet för de genererade bilderna. Skriver [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Specificerar om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Specificerar om hyperlänkar med JavaScript-anrop ska hoppas över vid sparning av presentationen. Skriv **bool**. Standardvärdet är **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Ställer in läget där bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Returnerar eller ställer in ett objekt som tar emot varningar och beslutar om laddningsprocessen ska fortsätta eller avbrytas. Skriver [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in det n-:te mallargumentet som en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
|  [TiffOptions](./tiffoptions/)() | Standardkonstruktor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-konstruktionen typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning med C#-statement lock(). Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar

Följande exempel visar hur man konverterar PowerPoint till TIFF med standardstorlek. 
```cpp
// Instansiera ett Presentation-objekt som representerar en presentationsfil
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// Sparar presentationen till TIFF-dokument
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
Följande exempel visar hur man konverterar PowerPoint till TIFF med anpassad storlek. 
```cpp
// Instansiera ett Presentation-objekt som representerar en presentationsfil
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// Instansiera TiffOptions-klassen
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// Ställer in komprimeringstyp
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// Komprimeringstyper
// Default - Anger standardkomprimeringsschemat (LZW).
// None - Anger ingen kompression.
// CCITT3
// CCITT4
// LZW
// RLE
// Depth beror på komprimeringstypen och kan inte ställas in manuellt.
// Upplösningsenheten är alltid lika med "2" (punkter per tum)
// Ställer in bildens DPI
opts->set_DpiX(200);
opts->set_DpiY(100);
// Ställ in bildstorlek
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// Spara presentationen till TIFF med angiven bildstorlek
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
Följande exempel visar hur man konverterar PowerPoint till TIFF med anpassat bildpixelformat. 
```cpp
// Instansiera ett Presentation-objekt som representerar en presentationsfil
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// Spara presentationen till TIFF med angiven bildstorlek
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## Se även

* Klass [SaveOptions](../saveoptions/)
* Klass [ITiffOptions](../itiffoptions/)
* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)