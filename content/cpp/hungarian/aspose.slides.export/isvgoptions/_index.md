---
title: ISVGOptions
second_title: Aspose.Slides for C++ API-referencia
description: Az SVG beállításokat képviseli.
type: docs
weight: 404
url: /hu/aspose.slides.export/isvgoptions/
---
## ISVGOptions osztály


Az SVG beállításokat képviseli.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN egy értékkel, beleértve a NaN-t, nem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN egy értékkel, beleértve a NaN-t, nem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Visszaadja a betűkészletet, amelyet akkor használ, ha a forrás betűkészlet nem található. Olvassa a [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | Logikai jelző, amely azt jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban lesznek sorosítva (ami esetleg nagyobb fájlt eredményez). Olvasás: **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | Megállapítja, hogy a 3D szöveg le van-e tiltva az SVG-ben. Olvasás: **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Értéket ad vissza, amely azt jelzi, hogy a szöveg ligatúrák használata nélkül van-e renderelve. Ha **true**, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság **false**. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | Letiltja a FromCornerX és FromCenter gradiens felosztását. Olvasás: **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | Az SVG 1.1 nem támogatja a jelölőkhöz tartozó beállítások definiálását. [Aspose.Slides](../../aspose.slides/) SVG író motorja megoldást kínál: levágja a vonal végét a nyíllal, így a vonal nem fed le jelölőket. Ez a beállítás kikapcsolja ezt a viselkedést. Olvasás: **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Meghatározza az externálisan betöltött betűkészletek kezelésének módját. Olvasás: [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Visszaadja a gradiens vizuális stílusát. Olvasás: [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Olyan beállításokat biztosít, amelyek a [Ink](../../aspose.slides.ink/) objektumok megjelenését szabályozzák az exportált dokumentumban. Csak olvasható: [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Meghatározza a JPEG kódolás minőségét. Olvasás: **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Visszaadja a metafájl rasterizációjának alsó felbontási határát. Olvasás: **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | A képek tömörítési szintjét jelöli. Olvasás: [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Egy visszahívási objektumot jelöl, amely a mentés előrehaladását százalékban jelzi. Lásd: [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Visszaadja és beállítja a visszahívási felületet, amely lehetővé teszi a felhasználó számára az alakzatkonverzió irányítását. Olvasás: [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Megadja, hogy a prezentáció mentésekor kihagyandók-e a JavaScript hívásokat tartalmazó hiperhivatkozások. Olvasás: **bool**. Alapértelmezett érték: **false**. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Megállapítja, hogy a renderelés során el kell-e végezni a megadott alakzatforgatást. Olvasás: **bool**. Alapértelmezett érték: **true**. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Megállapítja, hogy a szövegdoboz bekerül-e a renderelési területbe vagy sem. Olvasás: **bool**. Alapértelmezett érték: **false**. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Megállapítja, hogy a dián levő szöveg grafikai formában lesz-e mentve. Olvasás: **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Visszaad egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás: [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoláskonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoláskonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozással hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozással hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az érték típusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Beállítja a betűkészletet, amelyet a forrás betűkészlet hiánya esetén használ. Írás: [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | Logikai jelző, amely azt jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban lesznek sorosítva (ami esetleg nagyobb fájlt eredményez). Írás: **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | Megállapítja, hogy a 3D szöveg le van-e tiltva az SVG-ben. Írás: **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Beállít egy értéket, amely azt jelzi, hogy a szöveget ligatúrák használata nélkül renderelik-e. Ha **true**, a ligatúrák le lesznek tiltva a renderelt kimenetben. Alapértelmezés szerint ez a tulajdonság **false**. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | Letiltja a FromCornerX és FromCenter gradiens felosztását. Írás: **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | Az SVG 1.1 nem támogatja a jelölőkhöz tartozó beállítások definiálását. [Aspose.Slides](../../aspose.slides/) SVG író motorja megoldást kínál: levágja a vonal végét a nyíllal, így a vonal nem fed le jelölőket. Ez a beállítás kikapcsolja ezt a viselkedést. Írás: **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Meghatározza az externálisan betöltött betűkészletek kezelésének módját. Írás: [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Beállítja a gradiens vizuális stílusát. Írás: [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Meghatározza a JPEG kódolás minőségét. Írás: **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Beállítja a metafájl rasterizációjának alsó felbontási határát. Írás: **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | A képek tömörítési szintjét jelöli. Írás: [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Egy visszahívási objektumot jelöl, amely a mentés előrehaladását százalékban jelzi. Lásd: [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Visszaadja és beállítja a visszahívási felületet, amely lehetővé teszi a felhasználó számára az alakzatkonverzió irányítását. Írás: [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Megadja, hogy a prezentáció mentésekor kihagyandók-e a JavaScript hívásokat tartalmazó hiperhivatkozások. Írás: **bool**. Alapértelmezett érték: **false**. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Megállapítja, hogy a renderelés során el kell-e végezni a megadott alakzatforgatást. Írás: **bool**. Alapértelmezett érték: **true**. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Megállapítja, hogy a szövegdoboz bekerül-e a renderelési területbe vagy sem. Írás: **bool**. Alapértelmezett érték: **false**. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Megállapítja, hogy a dián lévő szöveg grafikai formában lesz-e mentve. Írás: **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Írás: [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók tárolókban való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [ISaveOptions](../isaveoptions/)
* Névtere [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)