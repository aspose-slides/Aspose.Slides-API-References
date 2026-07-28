---
title: TiffOptions
second_title: Aspose.Slides C++ API referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció TIFF formátumban.
type: docs
weight: 768
url: /hu/aspose.slides.export/tiffoptions/
---
## TiffOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció TIFF formátumban.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Ugyanazt a C#-stílusú lebegőpontos összehasonlítást szimulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Ugyanazt a C#-stílusú lebegőpontos összehasonlítást szimulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | Megadja a színes kép fekete-fehér képpé konvertálásának algoritmusát. Ez az opció csak akkor lesz alkalmazva, ha a [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) vagy [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) értékre van állítva. Olvassa [BlackWhiteConversionMode](../blackwhiteconversionmode/). Alapértelmezett: [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | Megadja a tömörítés típusát. Olvassa [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Visszaadja a használt betűtípust, ha a forrás betűtípus nem található. Olvassa [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | Megadja a vízszintes felbontást pont per hüvelykben. Olvassa **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | Megadja a függőleges felbontást pont per hüvelykben. Olvassa **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Visszaadja a gradient vizuális stílusát. Olvassa [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | Megadja a generált TIFF kép méretét. Az alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a bemutató dia mérete alapján lesznek kiszámítva. Olvassa [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Lehetőségeket biztosít, amelyek szabályozzák a [Ink](../../aspose.slides.ink/) objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | Megadja a generált képek pixelformátumát. Olvassa [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Egy visszahívási objektumot képvisel a százalékos mentési előrehaladás frissítéseihez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett: **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Olvassa **bool**. Az alapértelmezett érték **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Megadja azt a módot, amelyben a diák az oldalon elhelyezkednek a prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvassa [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciacs számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | Megadja a színes kép fekete-fehér képpé konvertálásának algoritmusát. Ez az opció csak akkor lesz alkalmazva, ha a [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) vagy [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) értékre van állítva. Írja [BlackWhiteConversionMode](../blackwhiteconversionmode/). Alapértelmezett: [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | Megadja a tömörítés típusát. Írja [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Beállítja a használandó betűtípust, ha a forrás betűtípus nem található. Írja [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | Megadja a vízszintes felbontást pont per hüvelykben. Írja **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | Megadja a függőleges felbontást pont per hüvelykben. Írja **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Beállítja a gradient vizuális stílusát. Írja [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Megadja a generált TIFF kép méretét. Az alapértelmezett érték 0x0, ami azt jelenti, hogy a generált képméretek a bemutató dia mérete alapján lesznek kiszámítva. Írja [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | Megadja a generált képek pixelformátumát. Írja [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Egy visszahívási objektumot képvisel a százalékos mentési előrehaladás frissítéseihez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett: **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Írja **bool**. Az alapértelmezett érték **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Beállítja azt a módot, amelyben a diák az oldalon elhelyezkednek a prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Írja [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonparamétert gyenge mutatóra (nem megosztottra). Lehetővé teszi a mutatók konténerekben gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [TiffOptions](./tiffoptions/)() |  |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzés

A következő példa bemutatja, hogyan konvertáljon PowerPoint-ot TIFF formátumba alapértelmezett mérettel.  
```cpp
// Létrehoz egy Presentation objektumot, amely egy bemutató fájlt képvisel
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// A bemutató mentése TIFF dokumentumba
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
A következő példa bemutatja, hogyan konvertáljon PowerPoint-ot TIFF formátumba egyedi mérettel.  
```cpp
// Létrehoz egy Presentation objektumot, amely egy Presentation fájlt képvisel
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// Létrehozza a TiffOptions osztályt
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// A tömörítés típusának beállítása
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// Tömörítési típusok
// Default - Meghatározza az alapértelmezett tömörítési sémát (LZW).
// None - Nincs tömörítés.
// CCITT3
// CCITT4
// LZW
// RLE
// A mélység a tömörítési típustól függ, és nem állítható be manuálisan.
// A felbontási egység mindig "2" (pont per hüvelyk)
// A képpont per hüvelyk (DPI) beállítása
opts->set_DpiX(200);
opts->set_DpiY(100);
// Kép méretének beállítása
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// A bemutató mentése TIFF-be a megadott képmérettel
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
A következő példa bemutatja, hogyan konvertáljon PowerPoint-ot TIFF formátumba egyedi képpixel formátummal.  
```cpp
// Létrehoz egy Presentation objektumot, amely egy Presentation fájlt képvisel
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// A bemutató mentése TIFF-be a megadott képmérettel
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## Lásd még

* Osztály [SaveOptions](../saveoptions/)
* Osztály [ITiffOptions](../itiffoptions/)
* Névtér [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)