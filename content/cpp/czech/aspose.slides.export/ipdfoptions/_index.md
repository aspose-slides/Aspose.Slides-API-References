---
title: IPdfOptions
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.
type: docs
weight: 274
url: /cs/aspose.slides.export/ipdfoptions/
---
## IPdfOptions třída

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro vnitřní účely. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být udělena při otevření dokumentu s uživatelským přístupem. Viz [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | Vrací pole uživatelem definovaných názvů rodin písem, které by [Aspose.Slides](../../aspose.slides/) mělo považovat za společné. Čtení [System::String](../../system/string/)[]. |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | Aplikuje zadanou průhlednou barvu na obrázek, pokud je **true**. |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | Určuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (namísto výchozí). Pokud je nastaveno na **bool**.true, pro každý obrázek v prezentaci bude zvolen nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu. |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | Požadovaná úroveň souladu pro generovaný PDF dokument. Čtení [PdfCompliance](../pdfcompliance/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Vrací písmo použité v případě, že není nalezeno zdrojové písmo. Čtení [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | True, pokud má být vykreslen černý rámec kolem každého slidu. Čtení **bool**. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | Určuje, zda mají být vloženy všechny znaky písma nebo jen použita podmnožina. Čtení **bool**. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | True, pokud mají být vloženy TrueType fonty pro ASCII znaky 32-127. [Fonts](../../aspose.slides/fonts/) pro kódy znaků vyšší než 127 jsou vždy vloženy. Čtení **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Vrací vizuální styl přechodu. Čtení [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | Získává průhlednou barvu obrázku. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | True, pokud se mají všechna data OLE z prezentace převést na vložené soubory ve výsledném PDF. Čtení **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Poskytuje možnosti, které řídí vzhled objektů [Ink](../../aspose.slides.ink/) v exportovaném dokumentu. Pouze pro čtení [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | Vrací hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Čtení **uint8_t**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Nastavení uživatelského hesla pro ochranu PDF dokumentu. Čtení [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Reprezentuje objekt zpětného volání pro ukládání aktualizací průběhu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | Udává, zda by měl být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné stylování. Tento přístup může zlepšit kvalitu textu v výsledném PDF pro určité fonty. Čtení **bool**. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | True, pokud mají být všechny metafily použité v prezentaci převedeny na PNG obrázky. Čtení **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Určuje, zda má generovaný dokument obsahovat skryté slidy, nebo ne. Výchozí hodnota je **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čtení **bool**. Výchozí hodnota je **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Získává režim, ve kterém jsou slidy umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | Vrací hodnotu určující rozlišení obrázků v PDF dokumentu. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | Určuje typ komprese, který bude použit pro celý textový obsah v dokumentu. Čtení [PdfTextCompression](../pdftextcompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Vrací objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Čtení [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává aktuální typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený počet referencí o zadanou hodnotu. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být udělena při otevření dokumentu s uživatelským přístupem. Viz [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Nastavuje pole uživatelem definovaných názvů rodin písem, které by [Aspose.Slides](../../aspose.slides/) mělo považovat za společné. Zápis [System::String](../../system/string/)[]. |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | Aplikuje zadanou průhlednou barvu na obrázek, pokud je **true**. |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | Indikuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (namísto výchozí). Pokud je nastaveno na **bool**.true, pro každý obrázek v prezentaci bude zvolen nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu. |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | Požadovaná úroveň souladu pro generovaný PDF dokument. Zápis [PdfCompliance](../pdfcompliance/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Nastavuje písmo použité v případě, že není nalezeno zdrojové písmo. Zápis [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | True, pokud má být vykreslen černý rámec kolem každého slidu. Zápis **bool**. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | Určuje, zda mají být vloženy všechny znaky písma nebo jen použita podmnožina. Zápis **bool**. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | True, pokud mají být vloženy TrueType fonty pro ASCII znaky 32-127. [Fonts](../../aspose.slides/fonts/) pro kódy znaků vyšší než 127 jsou vždy vloženy. Zápis **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Nastavuje vizuální styl přechodu. Zápis [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | Nastavuje průhlednou barvu obrázku. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | True, pokud se mají všechna OLE data z prezentace převést na vložené soubory ve výsledném PDF. Zápis **bool**. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | Nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Zápis **uint8_t**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Nastavení uživatelského hesla pro ochranu PDF dokumentu. Zápis [System::String](../../system/string/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Reprezentuje objekt zpětného volání pro ukládání aktualizací průběhu v procentech. Viz [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | Udává, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné stylování. Tento přístup může zlepšit kvalitu textu v výsledném PDF pro určité fonty. Zápis **bool**. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | True, pokud mají být všechny metafily použité v prezentaci převedeny na PNG obrázky. Zápis **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Určuje, zda má generovaný dokument obsahovat skryté slidy, nebo ne. Výchozí hodnota je **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Zápis **bool**. Výchozí hodnota je **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Nastavuje režim, ve kterém jsou slidy umístěny na stránku při exportu prezentace [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | Nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | Určuje typ komprese, který bude použit pro celý textový obsah v dokumentu. Zápis [PdfTextCompression](../pdftextcompression/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Zápis [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [ISaveOptions](../isaveoptions/)
* Jmenný prostor [Aspose::Slides::Export](../)
* Knihovna [Aspose.Slides](../../)