---
title: SwfOptions
second_title: Aspose.Slides for C++ API Referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik egy bemutató Swf formátumban.
type: docs
weight: 742
url: /hu/aspose.slides.export/swfoptions/
---
## SwfOptions osztály

Provides options that control how a presentation is saved in Swf format.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```


## Metódusok

| Method | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| **bool** [get_Compressed](./get_compressed/)() override | Megadja, hogy a generált SWF dokumentumot tömöríteni kell-e vagy sem. Alapértelmezett érték: **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Visszaadja a betűkészletet, amely akkor használatos, ha a forrás betűkészlet nem található. Olvassa [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Engedélyezi/letiltja a helyi menüt. Alapértelmezett érték true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Visszaadja a gradiens vizuális stílusát. Olvassa [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Megadja a JPEG képek minőségét. Alapértelmezett érték 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixel PNG képre kell lennie, különben a logó hibásan jelenhet meg. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Lekéri a logó teljes hiperhivatkozás címét. Csak akkor van hatása, ha a [set_LogoImageBytes()](./set_logoimagebytes/) meg van adva. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Egy visszahívási objektumot képvisel a mentés előrehaladásának százalékos frissítéseihez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Megjeleníti/elrejti az alsó panelt. A flashvars-ban felülírható. Alapértelmezett érték true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Megjeleníti/elrejti a teljes képernyős gombot. A flashvars-ban felülírható. Alapértelmezett érték true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Megjeleníti/elrejti a bal panelt. A flashvars-ban felülírható. Alapértelmezett érték true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Megadja, hogy legyen-e keret az oldalak körül. Alapértelmezett érték true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Megjeleníti/elrejti az oldal léptetőt. A flashvars-ban felülírható. Alapértelmezett érték true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Megjeleníti/elrejti a kereső szekciót. A flashvars-ban felülírható. Alapértelmezett érték true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Megjeleníti/elrejti a teljes felső panelt. A flashvars-ban felülírható. Alapértelmezett érték true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Olvas **bool**. Az alapértelmezett érték **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Lekéri azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek egy prezentáció [ISlidesLayoutOptions](../islideslayoutoptions/) exportálásakor. Ez a tulajdonság nem támogatja a [HandoutLayoutingOptions](../handoutlayoutingoptions/) típusú objektumok hozzárendelését. |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Elindul nyitott bal panellel. A flashvars-ban felülírható. Alapértelmezett érték false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentum megjelenítőt vagy sem. Alapértelmezett érték **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvassa [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó hivatkozásszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típusú példányt képvisel-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia összehasonlítja az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Megadja, hogy a generált SWF dokumentumot tömöríteni kell-e vagy sem. Alapértelmezett érték: **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Beállítja a betűkészletet, amely akkor használatos, ha a forrás betűkészlet nem található. Kiírja [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Engedélyezi/letiltja a helyi menüt. Alapértelmezett érték true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Beállítja a gradiens vizuális stílusát. Kiírja [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Megadja a JPEG képek minőségét. Alapértelmezett érték 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixel PNG képre kell lennie, különben a logó hibásan jelenhet meg. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Beállítja a logó teljes hiperhivatkozás címét. Csak akkor van hatása, ha a [set_LogoImageBytes()](./set_logoimagebytes/) meg van adva. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Egy visszahívási objektumot képvisel a mentés előrehaladásának százalékos frissítéseihez. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Megjeleníti/elrejti az alsó panelt. A flashvars-ban felülírható. Alapértelmezett érték true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Megjeleníti/elrejti a teljes képernyős gombot. A flashvars-ban felülírható. Alapértelmezett érték true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Megjeleníti/elrejti a bal panelt. A flashvars-ban felülírható. Alapértelmezett érték true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Megadja, hogy legyen-e keret az oldalak körül. Alapértelmezett érték true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Megjeleníti/elrejti az oldal léptetőt. A flashvars-ban felülírható. Alapértelmezett érték true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Megjeleníti/elrejti a kereső szekciót. A flashvars-ban felülírható. Alapértelmezett érték true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Megjeleníti/elrejti a teljes felső panelt. A flashvars-ban felülírható. Alapértelmezett érték true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Kiír **bool**. Az alapértelmezett érték **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Beállítja azt a módot, ahogyan a diák az oldalon elhelyeznek egy prezentáció [ISlidesLayoutOptions](../islideslayoutoptions/) exportálásakor. Ez a tulajdonság nem támogatja a [HandoutLayoutingOptions](../handoutlayoutingoptions/) típusú objektumok hozzárendelését. |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Elindul nyitott bal panellel. A flashvars-ban felülírható. Alapértelmezett érték false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Megadja, hogy a generált SWF dokumentum tartalmazza-e a beépített dokumentum megjelenítőt vagy sem. Alapértelmezett érték **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Kiír [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n'th sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [SwfOptions](./swfoptions/)() | Alapértelmezett konstruktor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzés

A következő példa bemutatja, hogyan lehet a PowerPoint-ot SWF Flash formátumba konvertálni. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## Lásd még

* Osztály [SaveOptions](../saveoptions/)
* Osztály [ISwfOptions](../iswfoptions/)
* Névtere [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)