---
title: PdfOptions
second_title: Aspose.Slides C++ API hivatkozás
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan menthető a bemutató PDF formátumban.
type: docs
weight: 573
url: /hu/aspose.slides.export/pdfoptions/
---
## PdfOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan menthető a bemutató PDF formátumban.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikájával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Egy halmaz flaget tartalmaz, amely meghatározza, hogy milyen hozzáférési engedélyek legyenek megadva a dokumentum felhasználói hozzáféréssel történő megnyitásakor. Lásd [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Visszaad egy tömböt a felhasználó által megadott betűkészlet-nevekkel, amelyeket a [Aspose.Slides](../../aspose.slides/) közösnek tekint. Olvasd el [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Alkalmazza a megadott átlátszó színt egy képre, ha **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Jelzi, hogy az egyes képekhez a leghatékonyabb tömörítést (az alapértelmezett helyett) automatikusan kell-e kiválasztani. Ha **bool**.true, minden képhez a prezentációban a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami a végső PDF dokumentum kisebb méretéhez vezet. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | A generált PDF dokumentum kívánt megfelelőségi szintje. Olvasd [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Visszaadja a használandó betűtípust, ha a forrás betűtípus nem található. Olvasd [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | True, ha fekete keretet kell rajzolni minden diára. Olvasd **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Meghatározza, hogy a betűtípus összes karaktere be legyen-e ágyazva, vagy csak a használt részhalmaz. Olvasd **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Meghatározza, hogy a [Aspose.Slides](../../aspose.slides/) beágyazza-e a közös betűtípusokat ASCII (33..127 kódtartomány) szövegre. [Fonts](../../aspose.slides/fonts/) a 127-nél nagyobb karakterkódok mindig beágyazottak. A közös betűtípusok listája tartalmazza a PDF alapértelmezett 14 betűtípusát és a felhasználó által megadott további betűtípusokat. Olvasd **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Visszaadja a gradient vizuális stílusát. Olvasd [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Lekéri a kép átlátszó színét. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | True, ha az összes OLE adatot a prezentációból a végső PDF-be beágyazott fájlokká kell konvertálni. Olvasd **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Lehetőségeket biztosít, amelyek a [Ink](../../aspose.slides.ink/) objektumok megjelenését szabályozzák az exportált dokumentumban. Csak olvasható [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Visszaad egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvasd **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasd [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Egy visszahívási objektumot képvisel a mentés folyamatának százalékos frissítéseihez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés javíthatja a szöveg minőségét a resultáló PDF-ben bizonyos betűtípusoknál. Olvasd **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | True, ha a prezentációban használt összes metafájl PNG képpé konvertálódik. Olvasd **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Meghatározza, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Meghatározza, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperlinkeket. Olvasd **bool**. Az alapértelmezett érték **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Lekéri azt a módot, amelyben a diák az oldalon helyezkednek el a prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Visszaad egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Megadja a dokumentum összes szöveges tartalmához használni kívánt tömörítési típust. Olvasd [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és dönt arról, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasd [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolatkészítését. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolatkészítését. |
|  [PdfOptions](./pdfoptions/)() | Alapértelmezett konstruktor. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Egy halmaz flaget tartalmaz, amely meghatározza, hogy milyen hozzáférési engedélyek legyenek megadva a dokumentum felhasználói hozzáféréssel történő megnyitásakor. Lásd [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Beállít egy tömböt a felhasználó által definiált betűkészlet-nevekkel, amelyeket a [Aspose.Slides](../../aspose.slides/) közösnek tekint. Írj [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Alkalmazza a megadott átlátszó színt egy képre, ha **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Jelzi, hogy az egyes képekhez a leghatékonyabb tömörítést (az alapértelmezett helyett) automatikusan kell-e kiválasztani. Ha **bool**.true, minden képhez a prezentációban a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami a végső PDF dokumentum kisebb méretéhez vezet. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | A generált PDF dokumentum kívánt megfelelőségi szintje. Írj [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Beállítja a használandó betűtípust, ha a forrás betűtípus nem található. Írja [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | True, ha fekete keretet kell rajzolni minden diára. Írj **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Meghatározza, hogy a betűtípus összes karaktere be legyen-e ágyazva, vagy csak a használt részhalmaz. Írj **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Meghatározza, hogy a [Aspose.Slides](../../aspose.slides/) beágyazza-e a közös betűtípusokat ASCII (33..127 kódtartomány) szöveghez. [Fonts](../../aspose.slides/fonts/) a 127-nél nagyobb karakterkódok mindig beágyazottak. A közös betűtípusok listája tartalmazza a PDF alapértelmezett 14 betűtípusát és a felhasználó által megadott további betűtípusokat. Írj **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Beállítja a gradient vizuális stílusát. Írj [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Beállítja a kép átlátszó színét. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | True, ha az összes OLE adatot a prezentációból a végső PDF-be beágyazott fájlokká kell konvertálni. Írj **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Írj **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Írj [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Egy visszahívási objektumot képvisel a mentés folyamatának százalékos frissítéseihez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés javíthatja a szöveg minőségét a resultáló PDF-ben bizonyos betűtípusoknál. Írj **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | True, ha a prezentációban használt összes metafájl PNG képpé konvertálódik. Írj **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Meghatározza, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Meghatározza, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperlinkeket. Írj **bool**. Az alapértelmezett érték **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Beállítja azt a módot, amelyben a diák az oldalon helyezkednek el a prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Megadja a dokumentum összes szöveges tartalmához használni kívánt tömörítési típust. Írj [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és dönt arról, hogy a betöltési folyamat folytatódik-e vagy megszakad. Írj [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívd közvetlenül vagy használd a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használj okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

A következő példa bemutatja, hogyan lehet PowerPoint-ot PDF-re konvertálni egyedi beállításokkal.
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Példányosítja a PdfOptions osztályt
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Beállítja a JPEG minőséget
pdfOptions->set_JpegQuality(90);
// Beállítja a metafájlok viselkedését
pdfOptions->set_SaveMetafilesAsPng(true);
// Beállítja a szöveg tömörítési szintjét
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Meghatározza a PDF szabványt
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Mentés PDF formátumban a bemutatót
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
A következő példa bemutatja, hogyan lehet PowerPoint-ot PDF-re konvertálni rejtett diákkal.
```cpp
// Példányosít egy Presentation osztályt, amely egy PowerPoint fájlt képvisel
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Példányosítja a PdfOptions osztályt
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Hozzáadja a rejtett diákat
pdfOptions->set_ShowHiddenSlides(true);
// Mentés PDF formátumban a bemutatót
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
A következő példa bemutatja, hogyan lehet PowerPoint-ot PDF-re konvertálni jelszóval védett PDF-ben.
```cpp
// Példányosít egy Presentation objektumot, amely egy PowerPoint fájlt képvisel
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Beállítja a PDF jelszót és a hozzáférési engedélyeket
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Mentés PDF formátumban a bemutatót
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
A következő példa bemutatja, hogyan lehet PowerPoint-ot PDF-re konvertálni jegyzetekkel.
```cpp
// Példányosít egy Presentation objektumot, amely egy bemutató fájlt képvisel
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

## Lásd még

* Osztály [SaveOptions](../saveoptions/)
* Osztály [IPdfOptions](../ipdfoptions/)
* Névtere [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)