---
title: IChartTitle
second_title: Aspose.Slides C++ API referencia
description: A diagramcím tulajdonságait képviseli.
type: docs
weight: 911
url: /hu/aspose.slides.charts/icharttitle/
---
## IChartTitle osztály

A diagramcím tulajdonságait képviseli.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicializálja a TextFrameForOverriding-ot a paraméterben megadott "text" szöveggel. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen megváltoztatja a szövegét. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Meghatározza a diagram elem tényleges magasságát. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Meghatározza a diagram elem tényleges szélességét. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Meghatározza a diagram elem tényleges x-pozícióját (bal), a diagram bal felső sarkához viszonyítva. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Meghatározza a diagram elem tényleges felső szélét a diagram bal felső sarkához viszonyítva. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | A diagram elem felső szélét adja vissza a diagram magasságának hányadosaként. Csak-olvasású **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Visszaadja a diagramot. Csak-olvasású [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Visszaadja a cím kitöltés, vonal és effekt stílusait. Csak-olvasású [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Meghatározza a diagram elem magasságát a diagram magasságának hányadosaként. Olvasható **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Meghatározza, hogy más diagram elemek felülírhatják-e a címet. Olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak-olvasású [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | A diagram elem jobb oldalát adja vissza a diagram szélességének hányadosaként. Csak-olvasású **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Visszaadja az alap diát. Csak-olvasású [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Visszaadja a diagram szövegformátumát. Csak-olvasású [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Gazdag formázott szöveget tartalmazhat. Ha ez a tulajdonság nem null, akkor ez a formázott szöveges érték felülírja az automatikusan generált szöveget. Az automatikusan generált szöveg a címke, az érték tengely megjelenítési egység címkéje, a tengelycím, a diagramcím, valamint a trendvonal felirata implicit tulajdonsága. Az automatikusan generált szöveget a [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) tulajdonság formázza. Csak-olvasású [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Meghatározza a diagram elem szélességét a diagram szélességének hányadosaként. Olvasható **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Meghatározza a diagram elem bal oldalát a diagram szélességének hányadosaként. Olvasható **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Meghatározza a diagram elem felső szélét a diagram magasságának hányadosaként. Olvasható **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektummal társított referenciacsounter adatstruktúráját. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték típusú objektumot referenciával hasonlít össze a nullptr-el. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacsontot a meghatározott értékkel. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Meghatározza a diagram elem magasságát a diagram magasságának hányadosaként. Írható **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Meghatározza, hogy más diagram elemek felülírhatják-e a címet. Írható **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Meghatározza a diagram elem szélességét a diagram szélességének hányadosaként. Írható **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Meghatározza a diagram elem bal oldalát a diagram szélességének hányadosaként. Írható **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Meghatározza a diagram elem felső szélét a diagram magasságának hányadosaként. Írható **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja be. Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsont aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsontot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsontot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsontot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsontot. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [ILayoutable](../ilayoutable/)
* Osztály [IOverridableText](../ioverridabletext/)
* Osztály [IActualLayout](../iactuallayout/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)