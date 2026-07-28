---
title: IPdfOptions
second_title: Aspose.Slides C++ API referenciája
description: Beállításokat biztosít, amelyek szabályozzák, hogyan mentődik egy prezentáció PDF formátumban.
type: docs
weight: 274
url: /hu/aspose.slides.export/ipdfoptions/
---
## IPdfOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció PDF formátumban.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | Olyan zászlók halmazát tartalmazza, amelyek meghatározzák, milyen hozzáférési engedélyeket kell biztosítani, amikor a dokumentumot felhasználói hozzáféréssel nyitják meg. Lásd [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | Visszaad egy tömböt a felhasználó által megadott betűcsalád-nevekkel, amelyeket a [Aspose.Slides](../../aspose.slides/) közösnek kell tekinteni. Olvasd [System::String](../../system/string/)[]. |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | A megadott átlátszó színt alkalmazza a képre, ha **true**. |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | Jelzi, hogy minden képnél a leghatékonyabb tömörítést (a default helyett) automatikusan kell-e kiválasztani. Ha **bool**.true értékre van beállítva, a prezentáció minden képe esetén a legmegfelelőbb tömörítési algoritmus kerül kiválasztásra, ami a kész PDF dokumentum kisebb méretéhez vezet. |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | A generált PDF dokumentum kívánt megfelelőségi szintje. Olvasd [PdfCompliance](../pdfcompliance/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Visszaadja azt a betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. Olvassa [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | Igaz, ha minden diára fekete keretet kell rajzolni. Olvasd **bool**. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | Megadja, hogy a betűtípus összes karaktere be legyen-e ágyazva, vagy csak egy részhalmaz. Olvasd **bool**. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | Igaz, ha a TrueType betűtípusokat be kell ágyazni az ASCII 32-127 karakterekhez. [Fonts](../../aspose.slides/fonts/) a 127-nél nagyobb karakterkódokhoz mindig be van ágyazva. Olvasd **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Visszaadja a gradient vizuális stílusát. Olvasd [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | Lekéri a kép átlátszó színét. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | Igaz, ha a prezentáció összes OLE adatát át kell konvertálni beágyazott fájlokként a létrejövő PDF-ben. Olvasd **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Lehetőségeket biztosít, amelyek szabályozzák a [Ink](../../aspose.slides.ink/) objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | Visszaad egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumon belül. Olvasd **uint8_t**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasd [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Egy visszahívási objektumot képvisel a mentési folyamat százalékos frissítéseihez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | Jelzi, hogy a szöveget bitmapként rasterezzék és PDF-be mentsék, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a kész PDF-ben. Olvasd **bool**. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | Igaz, ha a prezentációban használt összes metafájlt PNG képekké kell konvertálni. Olvasd **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Megadja, hogy a prezentáció mentésekor kihagyják-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasd **bool**. Az alapértelmezett érték **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Lekéri azt a módot, ahogyan a diák elhelyezkednek az oldalon prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | Visszaad egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | Megadja a dokumentum összes szöveges tartalmához használandó tömörítési típust. Olvasd [PdfTextCompression](../pdftextcompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Visszaad egy objektumot, amely figyelmeztetéseket kap, és meghatározza, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasd [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított hivatkozásszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat hivatkozás alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat hivatkozás alapján. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján összehasonlítja az értéktípusú objektumot a nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | Olyan zászlók halmazát tartalmazza, amelyek meghatározzák, milyen hozzáférési engedélyeket kell biztosítani, amikor a dokumentumot felhasználói hozzáféréssel nyitják meg. Lásd [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Beállít egy tömböt a felhasználó által megadott betűcsalád-nevekkel, amelyeket a [Aspose.Slides](../../aspose.slides/) közösnek kell tekinteni. Írja [System::String](../../system/string/)[]. |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | A megadott átlátszó színt alkalmazza a képre, ha **true**. |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | Jelzi, hogy minden képnél a leghatékonyabb tömörítést (az alapértelmezett helyett) automatikusan kell-e kiválasztani. Ha **bool**.true értékre van beállítva, a prezentáció minden képe esetén a legmegfelelőbb tömörítési algoritmus kerül kiválasztásra, ami a kész PDF dokumentum kisebb méretéhez vezet. |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | A generált PDF dokumentum kívánt megfelelőségi szintje. Írja [PdfCompliance](../pdfcompliance/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. Írja [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | Igaz, ha minden diára fekete keretet kell rajzolni. Írja **bool**. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | Megadja, hogy a betűtípus összes karaktere be legyen-e ágyazva, vagy csak egy részhalmaz. Írja **bool**. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | Igaz, ha a TrueType betűtípusokat be kell ágyazni az ASCII 32-127 karakterekhez. [Fonts](../../aspose.slides/fonts/) a 127-nél nagyobb karakterkódokhoz mindig be van ágyazva. Írja **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Beállítja a gradient vizuális stílusát. Írja [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | Beállítja a kép átlátszó színét. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | Igaz, ha a prezentáció összes OLE adatát beágyazott fájlokként a létrejövő PDF-ben kell konvertálni. Írja **bool**. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | Beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Írja **uint8_t**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Írja [System::String](../../system/string/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Egy visszahívási objektumot képvisel a mentési folyamat százalékos frissítéseihez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | Jelzi, hogy a szöveget bitmapként rasterezzék és PDF-be mentsék, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a kész PDF-ben. Írja **bool**. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | Igaz, ha a prezentációban használt összes metafájlt PNG képekké kell konvertálni. Írja **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Megadja, hogy a prezentáció mentésekor kihagyják-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Írja **bool**. Az alapértelmezett érték **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Beállítja azt a módot, ahogyan a diák elhelyezkednek az oldalon prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | Beállít egy értéket, amely meghatározza a képek felbontását a PDF dokumentumban. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | Megadja a dokumentum összes szöveges tartalmához használandó tömörítési típust. Írja [PdfTextCompression](../pdftextcompression/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Beállít egy objektumot, amely figyelmeztetéseket kap, és meghatározza, hogy a betöltési folyamat folytatódik-e vagy megszakad. Írja [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átváltását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [ISaveOptions](../isaveoptions/)
* Névterület [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)