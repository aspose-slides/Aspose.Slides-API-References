---
title: HtmlOptions
second_title: Aspose.Slides C++ API referencia
description: HTML exportálási beállításokat képvisel.
type: docs
weight: 118
url: /hu/aspose.slides.export/htmloptions/
---
## HtmlOptions osztály

HTML exportálási beállításokat képvisel.

```cpp
class HtmlOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::IHtmlOptions
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Visszaadja a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Olvassa [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Bool zászló jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban sorosítva lesznek (ami nagyobb fájlmérethez vezethet). |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Lekér egy értéket, amely azt jelzi, hogy a szöveg ligatúrák nélkül kerül-e renderelésre. Ha **true**, a ligatúrák le lesznek tiltva a kimenetben. Alapértelmezés szerint **false**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Visszaadja a gradient vizuális stílusát. Olvassa [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\> [get_HtmlFormatter](./get_htmlformatter/)() override | Visszaadja a HTML sablont. Olvassa [IHtmlFormatter](../ihtmlformatter/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Opciókat biztosít, amelyek szabályozzák a [Ink](../../aspose.slides.ink/) objektumok megjelenését az exportált dokumentumban. Csak olvasható [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Visszaad egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Olvassa **uint8_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | A képek tömörítési szintjét képviseli |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban adja meg. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezés **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Olvassa **bool**. Az alapértelmezett érték **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\> [get_SlideImageFormat](./get_slideimageformat/)() override | Visszaadja a dia képformátum opciókat. Olvassa [ISlideImageFormat](../islideimageformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Lekéri azt a módot, ahogyan a diák az oldalon helyezkednek el a prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **bool** [get_SvgResponsiveLayout](./get_svgresponsivelayout/)() override | Igaz, ha kizárja a szélesség és magasság attribútumokat az svg konténerből – ez reszponzív elrendezést eredményez. Hamis, egyébként. Olvassa **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvassa [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
|  [HtmlOptions](./htmloptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Létrehoz egy új [HtmlOptions](./) objektumot a visszahívás megadásával. |
|  [HtmlOptions](./htmloptions/)() | Létrehoz egy új [HtmlOptions](./) objektumot egyetlen HTML fájlba mentéshez. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zárolásra. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot referenciával hasonlít össze a nullptr használatával. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Írja [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Bool zászló jelzi, hogy a levágott részek a dokumentum részeként maradnak-e. Ha igaz, a levágott részek eltávolításra kerülnek, ha hamis, akkor a dokumentumban sorosítva lesznek (ami nagyobb fájlmérethez vezethet). |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Beállít egy értéket, amely jelzi, hogy a szöveg ligatúrák nélkül kerül-e renderelésre. Ha **true**, a ligatúrák le lesznek tiltva a kimenetben. Alapértelmezés szerint **false**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Beállítja a gradient vizuális stílusát. Írja [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_HtmlFormatter](./set_htmlformatter/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\>) override | Beállítja a HTML sablont. Írja [IHtmlFormatter](../ihtmlformatter/). |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Beállít egy értéket, amely meghatározza a JPEG képek minőségét a PDF dokumentumban. Írja **uint8_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | A képek tömörítési szintjét képviseli |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban adja meg. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezés **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Írja **bool**. Az alapértelmezett érték **false**. |
| void [set_SlideImageFormat](./set_slideimageformat/)([System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\>) override | Beállítja a dia képformátum opciókat. Írja [ISlideImageFormat](../islideimageformat/). |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Beállítja azt a módot, ahogyan a diák az oldalon helyezkednek el a prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SvgResponsiveLayout](./set_svgresponsivelayout/)(**bool**) override | Igaz, ha kizárja a szélesség és magasság attribútumokat az svg konténerből – ez reszponzív elrendezést eredményez. Hamis, egyébként. Írja **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Írja [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóval (nem megosztottal). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [SaveOptions](../saveoptions/)
* Osztály [IHtmlOptions](../ihtmloptions/)
* Névtere [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)