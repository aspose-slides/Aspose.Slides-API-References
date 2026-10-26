---
title: DataLabel
second_title: Aspose.Slides C++ API referencia
description: Sorozatcímkéket reprezentál.
type: docs
weight: 365
url: /hu/aspose.slides.charts/datalabel/
---
## DataLabel osztály


Sorozatcímkéket reprezentál.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## Metódusok

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicializálja a TextFrameForOverriding-et a paraméter "text" szöveggel. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen megváltoztatja a szövegét. |
| [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | Létrehoz egy új példányt a [DataLabel](./) osztályból. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Megadja a diagram elem tényleges magasságát. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Megadja a diagram elem tényleges szélességét. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Megadja a diagram elem tényleges x helyzetét (bal), a diagram bal felső sarkához képest. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Megadja a diagram elem tényleges felső pozícióját a bal felső sarokhoz képest. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a tényleges értékek lekéréséhez. Olvasható **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Alsó. Csak olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Visszaadja a szülő diagramot. Csak olvasható [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | Visszaadja az adatcímke formátumát. Csak olvasható [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | Visszaadja egy cím magasságát a diagram magasságának hányadaként. Olvasható **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | A hamis azt jelenti, hogy az adatcímke nem látható (és ezért minden Show*-flag (ShowValue, ...) hamis). Csak olvasható **bool**. |
| **float** [get_Right](./get_right/)() override | Jobb. Csak olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Visszaadja a szövegformátumot. Csak olvasható [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szövegérték felülírja az adatcímke automatikusan generált szövegét. Az adatcímke automatikusan generált szövege azt a szöveget jelenti, amelyet a ShowSeriesName, ShowValue, ... tulajdonságok kezelnek, és a TextFormatManager.TextFormat tulajdonsággal formázzák. Csak olvasható [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | Lekéri a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat::get(set)_ShowLabelValueFromCell tulajdonság igaz. |
| **float** [get_Width](./get_width/)() override | Visszaadja egy cím szélességét a diagram szélességének hányadaként. Olvasható **float**. |
| **float** [get_X](./get_x/)() override | Visszaadja egy cím x koordinátáját a diagram szélességének hányadaként. Olvasható **float**. |
| **float** [get_Y](./get_y/)() override | Visszaadja egy cím y koordinátáját a diagram magasságának hányadaként. Olvasható **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | Visszaadja a tényleges címke szöveget a [DataLabelFormat](../datalabelformat/) beállítások vagy a [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text() érték alapján. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| void [Hide](./hide/)() override | Az adatcímkét elrejti az összes Show*-flag (ShowValue, ...) hamis állapotra állításával. Az IsVisible hamis lesz ezután. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képezi-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) vigyázó objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlít egy értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Height](./set_height/)(**float**) override | Beállítja egy cím magasságát a diagram magasságának hányadaként. Írható **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Beállítja a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat::get(set)_ShowLabelValueFromCell tulajdonság igaz. |
| void [set_Width](./set_width/)(**float**) override | Beállítja egy cím szélességét a diagram szélességének hányadaként. Írható **float**. |
| void [set_X](./set_x/)(**float**) override | Beállítja egy cím x koordinátáját a diagram szélességének hányadaként. Írható **float**. |
| void [set_Y](./set_y/)(**float**) override | Beállítja egy cím y koordinátáját a diagram magasságának hányadaként. Írható **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge pointerre (a megosztott helyett). Lehetővé teszi a pointerek konténerben való gyenge módra való váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) vigyázó objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos pointereket vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IDataLabel](../idatalabel/)
* Osztály [IDOMObject](../../aspose.slides/idomobject/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)