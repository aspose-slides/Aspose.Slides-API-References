---
title: ChartTitle
second_title: Aspose.Slides C++ API referenciája
description: A diagramcím tulajdonságait reprezentálja.
type: docs
weight: 326
url: /hu/aspose.slides.charts/charttitle/
---
## ChartTitle osztály

A diagramcím tulajdonságait reprezentálja.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicializálja a TextFrameForOverriding-et a paraméterben „text” megadott szöveggel. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen módosítja a szövegét. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN egyik értékhez sem egyenlő, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN egyik értékhez sem egyenlő, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Meghatározza a diagram elem tényleges magasságát. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a valós értékek lekéréséhez. Olvasható **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Meghatározza a diagram elem tényleges szélességét. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a valós értékek lekéréséhez. Olvasható **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Meghatározza a diagram elem tényleges x-helyzetét (bal), a diagram bal felső sarkához viszonyítva. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a valós értékek lekéréséhez. Olvasható **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Meghatározza a diagram elem tényleges felső szélét a diagram bal felső sarkához viszonyítva. Hívja meg a [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metódust előtte a valós értékek lekéréséhez. Olvasható **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Alul. Csak olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Visszaadja a szülő diagramot. Csak olvasható [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Visszaadja a cím kitöltés, vonal és hatás stílusait. Csak olvasható [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Visszaadja a cím magasságát a diagram magasságának arányaként. Olvasható **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Meghatározza, hogy más diagram elemek átfedhetik-e a címet. Olvasható **bool**. |
| **float** [get_Right](./get_right/)() override | Jobb. Csak olvasható **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Visszaadja a szövegformátumot. Csak olvasható [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szöveges érték felülírja az automatikusan generált szöveget. Az automatikusan generált szöveg a címke adatcímkéjének, az értéktengely feliratának, a tengelycímnek, a diagramcímnek, a trendvonal címkéjének egy implicit tulajdonsága. Az automatikusan generált szöveg a [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) tulajdonsággal formázott. Csak olvasható [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Visszaadja a cím szélességét a diagram szélességének arányaként. Olvasható **float**. |
| **float** [get_X](./get_x/)() override | Visszaadja a cím x-koordinátáját a diagram szélességének arányaként. Olvasható **float**. |
| **float** [get_Y](./get_y/)() override | Visszaadja a cím y-koordinátáját a diagram magasságának arányaként. Olvasható **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot referenciával hasonlít össze nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_Height](./set_height/)(**float**) override | Beállítja a cím magasságát a diagram magasságának arányaként. Írjon **float**-t. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Meghatározza, hogy más diagram elemek átfedhetik-e a címet. Írjon **bool**-t. |
| void [set_Width](./set_width/)(**float**) override | Beállítja a cím szélességét a diagram szélességének arányaként. Írjon **float**-t. |
| void [set_X](./set_x/)(**float**) override | Beállítja a cím x-koordinátáját a diagram szélességének arányaként. Írjon **float**-t. |
| void [set_Y](./set_y/)(**float**) override | Beállítja a cím y-koordinátáját a diagram magasságának arányaként. Írjon **float**-t. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-dik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók tárolókban való átváltását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IChartTitle](../icharttitle/)
* Osztály [IDOMObject](../../aspose.slides/idomobject/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)