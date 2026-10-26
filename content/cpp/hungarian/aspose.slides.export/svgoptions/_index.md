---
title: SVGOptions
second_title: Aspose.Slides C++ API-referencia
description: SVG opciókat képvisel.
type: docs
weight: 703
url: /hu/aspose.slides.export/svgoptions/
---
## SVGOptions osztály

SVG opciókat képvisel.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő egyetlen értékkel sem, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő egyetlen értékkel sem, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Alapértelmezett beállításokat ad vissza. Csak olvasható [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Visszaadja a forrás betűtípus hiánya esetén használt betűtípust. Olvas [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Egy boolean jelző jelzi, hogy a levágott részek a dokumentum részét képezik-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban sorosítva lesznek (ami esetleg nagyobb fájlhoz vezethet). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Meghatározza, hogy a 3D szöveg le van-e tiltva az SVG-ben. Olvas **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Értéket ad vissza, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e renderelve. Ha **true**-ra van állítva, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Letiltja a FromCornerX és FromCenter gradientek felosztását. Olvas **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | Az SVG 1.1 nem képes a jelölők insetjeit meghatározni. [Aspose.Slides](../../aspose.slides/) SVG írómotor megoldást kínál a problémára: levágja a nyíllal ellátott vonal végét, így a vonal nem fed át a jelölőkre. Ez a beállítás kikapcsolja ezt a viselkedést. Olvas **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Meghatározza a külső betöltött betűtípusok kezelésének módját. Olvas [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Visszaadja a gradient vizuális stílusát. Olvas [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Lehetőségeket biztosít, amelyek szabályozzák a [Ink](../../aspose.slides.ink/) objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Meghatározza a JPEG kódolás minőségét. Olvas **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Visszaadja a metafil rasterizálás alacsony felbontású határát. Olvas **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | A képek tömörítési szintjét képviseli |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Egy visszahívási objektumot képvisel a százalékos előrehaladás mentésére. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Visszaadja és beállítja a visszahívási felületet, amely lehetővé teszi a felhasználó számára a alakzat konverziójának vezérlését. Olvas [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Visszaadja a legegyszerűbb és legkisebb SVG fájl generálás beállításait. Csak olvasható [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokkal ellátott hiperhivatkozásokat. Olvas **bool**. Az alapértelmezett érték **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Meghatározza, hogy a renderelés során végrehajtja-e a megadott alakzat-rotációt vagy sem. Olvas **bool**. Az alapértelmezett érték **true**. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Meghatározza, hogy a szövegkeret a renderelési területbe legyen-e beépítve vagy sem. Olvas **bool**. Az alapértelmezett érték **false**. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Meghatározza, hogy a dia szövege grafikaként legyen-e mentve. Olvas **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Visszaad egy objektumot, vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvas [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Visszaadja a legpontosabb SVG fájl generálás beállításait. Csak olvasható [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Beállítja a forrás betűtípus hiánya esetén használt betűtípust. Írja [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Egy boolean jelző jelzi, hogy a levágott részek a dokumentum részét képezik-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban sorosítva lesznek (ami esetleg nagyobb fájlhoz vezethet). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Meghatározza, hogy a 3D szöveg le van-e tiltva az SVG-ben. Írja **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Beállítja azt az értéket, amely jelzi, hogy a szöveg ligatúrák használata nélkül van-e renderelve. Ha **true**, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Letiltja a FromCornerX és FromCenter gradientek felosztását. Írja **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | Az SVG 1.1 nem képes a jelölők insetjeit meghatározni. [Aspose.Slides](../../aspose.slides/) SVG írómotor megoldást kínál a problémára: levágja a nyíllal ellátott vonal végét, így a vonal nem fed át a jelölőkre. Ez a beállítás letiltja ezt a viselkedést. Írja **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Meghatározza a külső betöltött betűtípusok kezelésének módját. Írja [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Beállítja a gradient vizuális stílusát. Írja [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Meghatározza a JPEG kódolás minőségét. Írja **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Beállítja a metafil rasterizálás alacsony felbontású határát. Írja **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | A képek tömörítési szintjét képviseli |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Egy visszahívási objektumot képvisel a százalékos előrehaladás mentésére. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Visszaadja és beállítja a visszahívási felületet, amely lehetővé teszi a felhasználó számára az alakzat konverziójának vezérlését. Írja [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívásokkal ellátott hiperhivatkozásokat. Írja **bool**. Az alapértelmezett érték **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Meghatározza, hogy a renderelés során végrehajtja-e a megadott alakzat-rotációt vagy sem. Írja **bool**. Az alapértelmezett érték **true**. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Meghatározza, hogy a szövegkeret a renderelési területbe legyen-e beépítve vagy sem. Írja **bool**. Az alapértelmezett érték **false**. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Meghatározza, hogy a dia szövege grafikaként legyen-e mentve. Írja **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Visszaad egy objektumot, vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Írja [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átváltását gyenge módba a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [SVGOptions](./svgoptions/)() | Inicializál egy új példányt a [SVGOptions](./) osztályból. |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Inicializál egy új példányt a [SVGOptions](./) osztályból, megadva a link beágyazási vezérlő objektumot. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [SaveOptions](../saveoptions/)
* Osztály [ISVGOptions](../isvgoptions/)
* Névtér [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)