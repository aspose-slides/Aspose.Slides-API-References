---
title: PdfOptions
second_title: Aspose.Slides pro C++ referenční příručka API
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.
type: docs
weight: 573
url: /cs/aspose.slides.export/pdfoptions/
---
## PdfOptions třída


Provides options that control how a presentation is saved in Pdf format.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnoty ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být udělena při otevření dokumentu s uživatelským přístupem. Viz [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Vrací pole uživatelem definovaných názvů rodin písem, které by [Aspose.Slides](../../aspose.slides/) měl považovat za běžné. Přečtěte si [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Aplikuje zadanou průhlednou barvu na obrázek, pokud je **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Určuje, zda má být pro každý obrázek automaticky vybráno nejúčinnější komprese (namísto výchozí). Pokud je nastavena na **bool**.true, pro každý obrázek v prezentaci bude vybrán nejvhodnější komprimační algoritmus, což povede k menší velikosti výsledného PDF dokumentu. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Požadovaná úroveň shody pro generovaný PDF dokument. Přečtěte si [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Vrací písmo použité v případě, že zdrojové písmo nebylo nalezeno. Přečtěte si [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | Pravda pro vykreslení černého rámečku kolem každého snímku. Přečtěte si **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Určuje, zda mají být vloženy všechny znaky písma nebo jen použita podmnožina. Přečtěte si **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Určuje, zda [Aspose.Slides](../../aspose.slides/) vloží běžná písma pro ASCII (rozsah kódů 33..127) text. [Fonts](../../aspose.slides/fonts/) pro kódy znaků větší než 127 jsou vždy vloženy. Seznam běžných písem zahrnuje základních 14 písem PDF a další uživatelem specifikovaná písma. Přečtěte si **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Vrací vizuální styl přechodu. Přečtěte si [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Získá průhlednou barvu obrázku. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | Pravda pro převod všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Přečtěte si **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Poskytuje možnosti, které řídí vzhled objektů [Ink](../../aspose.slides.ink/) v exportovaném dokumentu. Pouze pro čtení [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Vrací hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Přečtěte si **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Nastavení uživatelského hesla pro ochranu PDF dokumentu. Přečtěte si [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Reprezentuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučný styl. Tento přístup může zlepšit kvalitu textu ve výsledném PDF pro některá písma. Přečtěte si **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | Pravda pro převod všech metafilek použitých v prezentaci na PNG obrázky. Přečtěte si **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Určuje, zda má generovaný dokument zahrnovat skryté snímky nebo ne. Výchozí je **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Určuje, zda přeskočit hypertextové odkazy s voláním JavaScriptu při ukládání prezentace. Přečtěte si **bool**. Výchozí hodnota je **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Získá režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Vrací hodnotu určující rozlišení obrázků v PDF dokumentu. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Určuje typ komprese, který bude použit pro veškerý textový obsah v dokumentu. Přečtěte si [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Přečtěte si [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá aktuální typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# příkazu lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
|  [PdfOptions](./pdfoptions/)() | Výchozí konstruktor. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Speciální verze [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Speciální verze [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být udělena při otevření dokumentu s uživatelským přístupem. Viz [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Nastavuje pole uživatelem definovaných názvů rodin písem, které by [Aspose.Slides](../../aspose.slides/) měl považovat za běžné. Zapište [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Aplikuje zadanou průhlednou barvu na obrázek, pokud je **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Určuje, zda má být pro každý obrázek automaticky vybráno nejúčinnější komprese (namísto výchozí). Pokud je nastaveno na **bool**.true, pro každý obrázek v prezentaci bude vybrán nejvhodnější komprimační algoritmus, což povede k menší velikosti výsledného PDF dokumentu. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Požadovaná úroveň shody pro generovaný PDF dokument. Zapište [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Nastavuje písmo použité v případě, že zdrojové písmo nebylo nalezeno. Zapíše [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | Pravda pro vykreslení černého rámečku kolem každého snímku. Zapište **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Určuje, zda mají být vloženy všechny znaky písma nebo jen podmnožina. Zapište **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Určuje, zda [Aspose.Slides](../../aspose.slides/) vloží běžná písma pro ASCII (rozsah kódů 33..127) text. [Fonts](../../aspose.slides/fonts/) pro kódy znaků větší než 127 jsou vždy vloženy. Seznam běžných písem zahrnuje základních 14 písem PDF a další uživatelem specifikovaná písma. Zapište **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Nastavuje vizuální styl přechodu. Zapište [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Nastavuje průhlednou barvu obrázku. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | Pravda pro převod všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Zapište **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Zapište **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Nastavení uživatelského hesla pro ochranu PDF dokumentu. Zapište [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Reprezentuje objekt zpětného volání pro ukládání aktualizací postupu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučný styl. Tento přístup může zlepšit kvalitu textu ve výsledném PDF pro některá písma. Zapište **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | Pravda pro převod všech metafilek použitých v prezentaci na PNG obrázky. Zapište **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Určuje, zda má generovaný dokument zahrnovat skryté snímky nebo ne. Výchozí je **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Určuje, zda přeskočit hypertextové odkazy s voláním JavaScriptu při ukládání prezentace. Zapište **bool**. Výchozí hodnota je **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Nastavuje režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Určuje typ komprese, který bude použit pro veškerý textový obsah v dokumentu. Zapište [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Zapište [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech na slabý režim. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# příkazu lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač odkazů. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Poznámky





Následující příklad ukazuje, jak převést PowerPoint do PDF s vlastními možnostmi.
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Vytvoří instanci třídy PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Nastaví kvalitu Jpeg
pdfOptions->set_JpegQuality(90);
// Nastaví chování pro metafily
pdfOptions->set_SaveMetafilesAsPng(true);
// Nastaví úroveň komprese textu
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Definuje standard PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Uloží prezentaci jako PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Následující příklad ukazuje, jak převést PowerPoint do PDF se skrytými snímky.
```cpp
// Vytvoří instanci třídy Presentation, která představuje soubor PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Vytvoří instanci třídy PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Přidá skryté snímky
pdfOptions->set_ShowHiddenSlides(true);
// Uloží prezentaci jako PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Následující příklad ukazuje, jak převést PowerPoint do PDF chráněného heslem.
```cpp
// Vytvoří objekt Presentation, který představuje soubor PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Nastaví heslo PDF a přístupová oprávnění
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Uloží prezentaci jako PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 Následující příklad ukazuje, jak převést PowerPoint do PDF s poznámkami.
```cpp
// Instantiate a Presentation object that represents a presentation file
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Viz také

* Třída [SaveOptions](../saveoptions/)
* Třída [IPdfOptions](../ipdfoptions/)
* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)