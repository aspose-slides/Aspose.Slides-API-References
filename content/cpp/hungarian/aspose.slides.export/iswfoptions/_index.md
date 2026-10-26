---
title: ISwfOptions
second_title: Aspose.Slides for C++ API Referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik el egy bemutató SWF formátumban.
type: docs
weight: 469
url: /hu/aspose.slides.export/iswfoptions/
---
## ISwfOptions osztály


Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik el egy bemutató SWF formátumban.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Megadja, hogy a létrehozott SWF dokumentum tömörítve legyen-e vagy sem. Alapértelmezett **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Visszaadja a forrásbetűtípus nem található esetén használt betűtípust. Olvassa [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | A helyi menü engedélyezése/tiltása. Alapértelmezett true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Visszaadja a gradient vizuális stílusát. Olvassa [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Megadja a JPEG képek minőségét.\n\n Alapértelmezett 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Kép, amely a néző jobb felső sarkában logóként jelenik meg.\n\n A képnek 32x64 pixeles PNG-nek kell lennie, ellenkező esetben a logó helytelenül jelenhet meg. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Lekéri a logó teljes hiperhivatkozás címét. Csak akkor hat, ha egy [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) van megadva. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban adja vissza. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Alsó panel megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Teljes képernyő gomb megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Megadja, hogy a létrehozott dokumentum tartalmazzon-e rejtett diákot. Alapértelmezett **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Bal panel megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Megadja, hogy megjelenjen-e a lapok körüli keret. Alapértelmezett true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Oldal léptető megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Keresési szakasz megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Teljes felső panel megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Megadja, hogy a mentés során kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvassa **bool**. Az alapértelmezett érték **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Lekéri a módot, amelyben a diák a lapon helyezkednek el egy prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). Ez a tulajdonság nem támogatja a **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** típusú objektumok hozzárendelését. |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Bal panel megnyitott állapotban indul. Felülírható flashvars-ban. Alapértelmezett false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Megadja, hogy a létrehozott SWF dokumentum tartalmazza-e a beépített dokumentumnézőt. Alapértelmezett **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Visszaad egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvassa [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal kapcsolatos referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-olását. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacsámlálót a megadott értékkel. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Megadja, hogy a létrehozott SWF dokumentum tömörítve legyen-e vagy sem. Alapértelmezett **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Beállítja a forrásbetűtípus nem található esetén használt betűtípust. Írja [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | A helyi menü engedélyezése/tiltása. Alapértelmezett true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Beállítja a gradient vizuális stílusát. Írja [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Megadja a JPEG képek minőségét.\n\n Alapértelmezett 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Kép, amely a néző jobb felső sarkában logóként jelenik meg.\n\n A képnek 32x64 pixeles PNG-nek kell lennie, ellenkező esetben a logó helytelenül jelenhet meg. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Beállítja a logó teljes hiperhivatkozás címét. Csak akkor hat, ha egy [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) van megadva. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Egy visszahívási objektumot képvisel, amely a mentés előrehaladását százalékban adja vissza. Lásd [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Alsó panel megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Teljes képernyő gomb megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Megadja, hogy a létrehozott dokumentum tartalmazzon-e rejtett diákot. Alapértelmezett **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Bal panel megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Megadja, hogy megjelenjen-e a lapok körüli keret. Alapértelmezett true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Oldal léptető megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Keresési szakasz megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Teljes felső panel megjelenítése/elrejtése. Felülírható flashvars-ban. Alapértelmezett true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Megadja, hogy a mentés során kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Írja **bool**. Az alapértelmezett érték **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Beállítja a módot, amelyben a diák a lapon helyezkednek el egy prezentáció exportálásakor [ISlidesLayoutOptions](../islideslayoutoptions/). Ez a tulajdonság nem támogatja a **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** típusú objektumok hozzárendelését. |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Bal panel megnyitott állapotban indul. Felülírható flashvars-ban. Alapértelmezett false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Megadja, hogy a létrehozott SWF dokumentum tartalmazza-e a beépített dokumentumnézőt. Alapértelmezett **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Írja [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerekben gyenge módra való átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [ISaveOptions](../isaveoptions/)
* Névterület [Aspose::Slides::Export](../)
* Könyvtár [Aspose.Slides](../../)