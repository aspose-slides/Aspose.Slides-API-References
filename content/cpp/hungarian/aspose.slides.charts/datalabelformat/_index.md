---
title: DataLabelFormat
second_title: Aspose.Slides C++ API Referencia
description: A DataLabel formázási beállításait képviseli.
type: docs
weight: 391
url: /hu/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat osztály

A [DataLabel](../datalabel/) formázási lehetőségeit képviseli.

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Metódusok

| Módszer | Leírás |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Összehasonlítja a megadott objektummal. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Visszaadja a diagramot. Csak olvasható [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | A adatcímke formátumát képviseli. Csak olvasható [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Olvas **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | A DataLabels objektum formátumkarakterláncát képviseli. Olvas [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Visszaadja a Parent_Immediate objektumot. Csak olvasható [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Visszaadja a szülő [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Csak olvasható [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | A adatcímke pozícióját képviseli. Olvas [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Beállít vagy visszaad egy Variant-et, amely a diagramon lévő adatcímkék elválasztóját képviseli. Olvas [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Megjeleníti egy adott diagram adatcímkéjének buborékméret értékének megjelenítési viselkedését. True – megjeleníti a buborékméret értéket. False – elrejti. Olvas **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Megjeleníti egy adott diagram adatcímkéjének kategórianév megjelenítési viselkedését. True – megjeleníti a kategórianévét a diagram adatcímkéin. False – elrejti. Olvas **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Meghatározza, hogy egy adott diagram adatcímkéje adatcalloutként vagy adatcímkéként jelenik meg. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Megjeleníti egy adott diagram adatcímkéjének cellaérték megjelenítési viselkedését. True – megjeleníti a cellaértéket. False – elrejti. Olvas **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Megjeleníti egy adott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését. True – megjeleníti a vezetővonalakat. False – elrejti. Olvas **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Megjeleníti egy adott diagram adatcímkéjének legenda kulcs megjelenítési viselkedését. True – ha a legenda kulcs látható. Olvas **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Megjeleníti egy adott diagram adatcímkéjének százalékérték megjelenítési viselkedését. True – megjeleníti a százalékértéket. False – elrejti. Olvas **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Visszaad egy Boolean értéket, amely jelzi a diagram adatcímkéinél a sorozatnév megjelenítési viselkedését. True – megjeleníti a sorozatnevet. False – elrejti. Olvas **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Megjeleníti egy adott diagram adatcímkéjének százalékérték megjelenítési viselkedését. True – megjeleníti a százalékértéket. False – elrejti. Olvas **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Visszaadja a diagram szövegformátumát. Csak olvasható [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekérdezi az objektumhoz kapcsolódó hivatkozásszámláló adatstruktúrát. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Visszaadja a hash kódot. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekérdezi az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyéni típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit sem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolási konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott hivatkozásszámlálót a megadott értékkel. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Ír **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | A DataLabels objektum formátumkarakterláncát képviseli. Ír [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | A adatcímke pozícióját képviseli. Ír [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Beállít vagy visszaad egy Variant-et, amely a diagramon lévő adatcímkék elválasztóját képviseli. Ír [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Megjeleníti egy adott diagram adatcímkéjének buborékméret értékének megjelenítési viselkedését. True – megjeleníti a buborékméret értéket. False – elrejti. Ír **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Megjeleníti egy adott diagram adatcímkéjének kategórianév megjelenítési viselkedését. True – megjeleníti a kategórianévét a diagram adatcímkéin. False – elrejti. Ír **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Meghatározza, hogy egy adott diagram adatcímkéje adatcalloutként vagy adatcímkéként jelenik meg. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Megjeleníti egy adott diagram adatcímkéjének cellaérték megjelenítési viselkedését. True – megjeleníti a cellaértéket. False – elrejti. Ír **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Megjeleníti egy adott diagram adatcímkéjének vezetővonalak megjelenítési viselkedését. True – megjeleníti a vezetővonalakat. False – elrejti. Ír **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Megjeleníti egy adott diagram adatcímkéjének legenda kulcs megjelenítési viselkedését. True – ha a legenda kulcs látható. Ír **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Megjeleníti egy adott diagram adatcímkéjének százalékérték megjelenítési viselkedését. True – megjeleníti a százalékértéket. False – elrejti. Ír **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Beállít egy Boolean értéket, amely jelzi a sorozatnév megjelenítési viselkedését a diagram adatcímkéinél. True – megjeleníti a sorozatnevet. False – elrejti. Ír **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Megjeleníti egy adott diagram adatcímkéjének százalékérték megjelenítési viselkedését. True – megjeleníti a százalékértéket. False – elrejti. Ír **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekérdezi a megosztott hivatkozásszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyéni objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őr objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge hivatkozásszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [PVIObject](../../aspose.slides/pviobject/)
* Osztály [IDataLabelFormat](../idatalabelformat/)
* Névtere [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)