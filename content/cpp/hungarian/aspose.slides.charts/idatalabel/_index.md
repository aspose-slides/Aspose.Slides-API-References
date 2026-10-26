---
title: IDataLabel
second_title: Aspose.Slides C++ API-referencia
description: Egy sor címkéit képviseli.
type: docs
weight: 937
url: /hu/aspose.slides.charts/idatalabel/
---
## IDataLabel osztály


Represents a series labels.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicializálja a TextFrameForOverriding objektumot a \"text\" paraméterben megadott szöveggel. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen megváltoztatja a szövegét. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szintaxis szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értékkel, így a NaN-nal sem, nem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értékkel, így a NaN-nal sem, nem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Meghatározza a diagram elem tényleges magasságát. Hívja előbb a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a valós értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Meghatározza a diagram elem tényleges szélességét. Hívja előbb a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a valós értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Meghatározza a diagram elem tényleges x-helyzetét (bal), a diagram bal felső sarkához viszonyítva. Hívja előbb a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a valós értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Meghatározza a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest. Hívja előbb a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust a valós értékek lekéréséhez. Olvasható **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | A diagram elem tetejét adja vissza a diagram magasságának arányaként. Csak-olvasású **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Visszaadja a diagramot. Csak-olvasású [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Visszaadja az adatcímke formátumát. Csak-olvasású [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Meghatározza a diagram elem magasságát a diagram magasságának arányaként. Olvasható **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | A hamis érték azt jelenti, hogy az adatcímke nem látható (és ezért minden Show*-jelző (ShowValue, ...) hamis). Csak-olvasású **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak-olvasású [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | A diagram elem jobb oldalát adja vissza a diagram szélességének arányaként. Csak-olvasású **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Visszaadja az alapdiát. Csak-olvasású [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Visszaadja a diagram szövegformátumát. Csak-olvasású [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szövegérték felülírja az automatikusan generált szöveget. Az automatikusan generált szöveg egy implicit tulajdonság az adatcímkén, az értéktengely megjelenítő egységcímkéjén, a tengely címén, a diagram címén, a trendvonal címkéjén. Az automatikusan generált szöveg a [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) tulajdonsággal formázható. Csak-olvasású [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Lekéri a munkafüzet adatc cellát. Akkor alkalmazandó, ha az IDataLabelFormat::get(set)_ShowLabelValueFromCell tulajdonság igaz. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Meghatározza a diagram elem szélességét a diagram szélességének arányaként. Olvasható **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Meghatározza a diagram elem x-helyzetét (bal) a diagram szélességének arányaként. Olvasható **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Meghatározza a diagram elem tetejét a diagram magasságának arányaként. Olvasható **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | Visszaadja a tényleges címkeszöveget a [DataLabelFormat](../datalabelformat/) beállításai vagy a TextFrameForOverriding.Text értéke alapján. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri a objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual void [Hide](./hide/)() | Az adatcímkét elrejti az összes Show*-jelző (ShowValue, ...) hamis állapotra állításával. Az IsVisible ezután hamis lesz. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típusú példány-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) figyelő objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak inicializál egy új objektumot és lehetővé teszi alosztályok másolását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak inicializál egy új objektumot és lehetővé teszi alosztályok másolását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektum referenciával való összehasonlítása nullptr-vel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Meghatározza a diagram elem magasságát a diagram magasságának arányaként. Írható **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Beállítja a munkafüzet adatcellát. Akkor alkalmazandó, ha az IDataLabelFormat::get(set)_ShowLabelValueFromCell tulajdonság igaz. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Meghatározza a diagram elem szélességét a diagram szélességének arányaként. Írható **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Meghatározza a diagram elem x-helyzetét (bal) a diagram szélességének arányaként. Írható **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Meghatározza a diagram elem tetejét a diagram magasságának arányaként. Írható **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge pointerre (nem megosztott) állítja. Lehetővé teszi a pointerek átváltását gyenge módba konténerekben. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) figyelő objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [ILayoutable](../ilayoutable/)
* Osztály [IOverridableText](../ioverridabletext/)
* Osztály [IActualLayout](../iactuallayout/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)