---
title: PdfOptions
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller alternativ som styr hur en presentation sparas i Pdf-format.
type: docs
weight: 573
url: /sv/aspose.slides.export/pdfoptions/
---
## PdfOptions klass

Tillhandahåller alternativ som styr hur en presentation sparas i Pdf-format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Innehåller en uppsättning flaggor som anger vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Returnerar en array av användardefinierade namn på teckensnittsfamiljer som [Aspose.Slides](../../aspose.slides/) bör betraktas som gemensamma. Läs [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Tillämpar den angivna transparenta färgen på en bild om **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Anger om den mest effektiva komprimeringen (istället för standard) för varje bild ska väljas automatiskt. Om satt till **bool**.true, kommer den mest lämpliga komprimeringsalgoritmen att väljas för varje bild i presentationen, vilket leder till en mindre storlek på den resulterande PDF-dokumentet. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Önskad kompatibilitetsnivå för genererat PDF-dokument. Läs [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Returnerar teckensnitt som används om källteckensnittet inte hittas. Läser [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | True för att rita en svart ram runt varje bild. Läs **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Bestämmer om alla tecken i teckensnittet ska bäddas in eller bara en använd delmängd. Läs **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Bestämmer om [Aspose.Slides](../../aspose.slides/) kommer att bädda in vanliga teckensnitt för ASCII (33..127 kodintervall) text. [Fonts](../../aspose.slides/fonts/) för teckenkoder större än 127 är alltid inbäddade. Listan med vanliga teckensnitt inkluderar PDFs grundläggande 14 teckensnitt och ytterligare användardefinierade teckensnitt. Läs **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Returnerar den visuella stilen för gradienten. Läs [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Hämtar bildens transparenta färg. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | True för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF:n. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Tillhandahåller alternativ som styr utseendet på [Ink](../../aspose.slides.ink/)-objekt i exporterat dokument. Endast läsbar [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Returnerar ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. Läs **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Anger användarlösenord för att skydda PDF-dokumentet. Läs [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Anger om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stöder fet stil. Detta tillvägagångssätt kan förbättra textkvaliteten i den resulterande PDF:n för vissa teckensnitt. Läs **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | True för att konvertera alla metafiler som används i en presentation till PNG-bilder. Läs **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Läs **bool**. Standardvärdet är **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Hämtar läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Returnerar ett värde som bestämmer upplösningen på bilder i PDF-dokumentet. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Anger komprimeringstyp som ska användas för allt textinnehåll i dokumentet. Läs [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Returnerar eller sätter ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Läs [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Aktiverar kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [PdfOptions](./pdfoptions/)() | Standardkonstruktor. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referens-jämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Innehåller en uppsättning flaggor som anger vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst. Se [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Ställer in en array av användardefinierade namn på teckensnittsfamiljer som [Aspose.Slides](../../aspose.slides/) bör betraktas som gemensamma. Skriv [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Tillämpar den angivna transparenta färgen på en bild om **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Anger om den mest effektiva komprimeringen (istället för standard) för varje bild ska väljas automatiskt. Om satt till **bool**.true, kommer den mest lämpliga komprimeringsalgoritmen att väljas för varje bild i presentationen, vilket leder till en mindre storlek på den resulterande PDF-dokumentet. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Önskad kompatibilitetsnivå för genererat PDF-dokument. Skriv [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Ställer in teckensnitt som används om källteckensnittet inte hittas. Skriver [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | True för att rita en svart ram runt varje bild. Skriv **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Bestämmer om alla tecken i teckensnittet ska bäddas in eller bara en delmängd används. Skriv **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Bestämmer om [Aspose.Slides](../../aspose.slides/) kommer att bädda in vanliga teckensnitt för ASCII (33..127 kodintervall) text. [Fonts](../../aspose.slides/fonts/) för teckenkoder större än 127 är alltid inbäddade. Listan med vanliga teckensnitt inkluderar PDFs bas 14 teckensnitt och ytterligare användardefinierade teckensnitt. Skriv **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Ställer in den visuella stilen för gradienten. Skriv [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Ställer in bildens transparenta färg. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | True för att konvertera all OLE-data från presentationen till inbäddade filer i den resulterande PDF:n. Skriv **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Ställer in ett värde som bestämmer kvaliteten på JPEG-bilderna i PDF-dokumentet. Skriv **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Anger användarlösenord för att skydda PDF-dokumentet. Skriv [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representerar ett återuppringningsobjekt för att spara framstegsuppdateringar i procent. Se [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Anger om text ska rasteriseras som en bitmap och sparas till PDF när teckensnittet inte stöder fet stil. Detta tillvägagångssätt kan förbättra textkvaliteten i den resulterande PDF:n för vissa teckensnitt. Skriv **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | True för att konvertera alla metafiler som används i en presentation till PNG-bilder. Skriv **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Anger om det genererade dokumentet ska inkludera dolda bilder eller inte. Standard är **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Anger om hyperlänkar med JavaScript-anrop ska hoppas över när presentationen sparas. Skriv **bool**. Standardvärdet är **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Ställer in läget i vilket bilder placeras på sidan vid export av en presentation [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Ställer in ett värde som bestämmer upplösningen på bilder i PDF-dokumentet. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Anger komprimeringstyp som ska användas för allt textinnehåll i dokumentet. Skriv [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Returnerar eller sätter ett objekt som tar emot varningar och bestämmer om laddningsprocessen ska fortsätta eller avbrytas. Skriv [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar

Följande exempel visar hur man konverterar PowerPoint till PDF med anpassade alternativ. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instansierar PdfOptions-klassen
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Sätter JPEG-kvaliteten
pdfOptions->set_JpegQuality(90);
// Sätter beteendet för metafiler
pdfOptions->set_SaveMetafilesAsPng(true);
// Sätter textkomprimeringsnivån
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Definierar PDF-standarden
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Sparar presentationen som en PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
Följande exempel visar hur man konverterar PowerPoint till PDF med dolda bilder. 
```cpp
// Instansierar en Presentation-klass som representerar en PowerPoint-fil
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instansierar PdfOptions-klassen
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Lägger till dolda bilder
pdfOptions->set_ShowHiddenSlides(true);
// Sparar presentationen som en PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
Följande exempel visar hur man konverterar PowerPoint till lösenordsskyddad PDF. 
```cpp
// Instansierar ett Presentation-objekt som representerar en PowerPoint-fil
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Anger PDF-lösenord och åtkomstbehörigheter
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Sparar presentationen som en PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
Följande exempel visar hur man konverterar PowerPoint till PDF med anteckningar. 
```cpp
// Instansierar ett Presentation-objekt som representerar en presentationsfil
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Ställer in bildtyp och storlek
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Se även

* Klass [SaveOptions](../saveoptions/)
* Klass [IPdfOptions](../ipdfoptions/)
* Namnrymd [Aspose::Slides::Export](../)
* Bibliotek [Aspose.Slides](../../)