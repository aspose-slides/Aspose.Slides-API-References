---
title: IDataLabelFormat
second_title: Aspose.Slides for C++ API referencia
description: A DataLabel formázási beállításait képviseli.
type: docs
weight: 963
url: /hu/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat osztály


Represents formatting options for [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Visszaadja a diagramot. Csak olvasható [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | A adatcímke formátumát reprezentálja. Csak olvasható [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Olvasható **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | A DataLabels objektum formátum stringjét reprezentálja. Olvasható [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Az adatcímke pozícióját reprezentálja. Olvasható [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak olvasható [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Beállít vagy visszaad egy Variant-ot, amely a diagram adatcímkéiben használt elválasztót reprezentálja. Olvasható [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Egy megadott diagram adatcímke buborékméret-érték megjelenítési viselkedését reprezentálja. True esetén megjeleníti a buborékméretet, False esetén elrejti. Olvasható **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Egy megadott diagram adatcímke kategórianév megjelenítési viselkedését reprezentálja. True esetén megjeleníti a kategórianévét a diagramon, False esetén elrejti. Olvasható **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Meghatározza, hogy egy megadott diagram adatcímkéje adatfelhívásként vagy adatcímkeként jelenik meg. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Egy megadott diagram adatcímke cellaérték megjelenítési viselkedését reprezentálja. True esetén megjeleníti a cellaértéket, False esetén elrejti. Olvasható **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Egy megadott diagram adatcímke vezetővonalak megjelenítési viselkedését reprezentálja. True esetén megjeleníti a vezetővonalakat, False esetén elrejti. Olvasható **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Egy megadott diagram adatcímke legendakulcs megjelenítési viselkedését reprezentálja. True, ha a legendakulcs látható. Olvasható **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Egy megadott diagram adatcímke százalékérték megjelenítési viselkedését reprezentálja. True esetén megjeleníti a százalékértéket, False esetén elrejti. Olvasható **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Visszaad egy logikai értéket, amely jelzi a sorozatnév megjelenítési viselkedését a diagram adatcímkéin. True esetén megjeleníti a sorozatnevet, False esetén elrejti. Olvasható **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Egy megadott diagram adatcímke százalékérték megjelenítési viselkedését reprezentálja. True esetén megjeleníti a százalékértéket, False esetén elrejti. Olvasható **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Visszaadja az alap diát. Csak olvasható [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Visszaadja a diagram szövegformátumát. Csak olvasható [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívható közvetlenül vagy a [LockContext](../../system/lockcontext/) sentinel objektummal. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozás alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hivatkozással hasonlít össze a nullptr-al. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Ír **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | A DataLabels objektum formátum stringjét reprezentálja. Ír [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Az adatcímke pozícióját reprezentálja. Ír [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Beállít vagy visszaad egy Variant-ot, amely a diagram adatcímkéiben használt elválasztót reprezentálja. Ír [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Egy megadott diagram adatcímke buborékméret-érték megjelenítési viselkedését reprezentálja. True esetén megjeleníti, False elrejti. Ír **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Egy megadott diagram adatcímke kategórianév megjelenítési viselkedését reprezentálja. True esetén megjeleníti, False elrejti. Ír **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Meghatározza, hogy egy megadott diagram adatcímkéje adatfelhívásként vagy adatcímkeként jelenik meg. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Egy megadott diagram adatcímke cellaérték megjelenítési viselkedését reprezentálja. True esetén megjeleníti, False elrejti. Ír **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Egy megadott diagram adatcímke vezetővonalak megjelenítési viselkedését reprezentálja. True esetén megjeleníti, False elrejti. Ír **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Egy megadott diagram adatcímke legendakulcs megjelenítési viselkedését reprezentálja. True, ha a legendakulcs látható. Ír **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Egy megadott diagram adatcímke százalékérték megjelenítési viselkedését reprezentálja. True esetén megjeleníti, False elrejti. Ír **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Beállít egy logikai értéket, amely jelzi a sorozatnév megjelenítési viselkedését a diagram adatcímkéin. True esetén megjeleníti, False elrejti. Ír **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Egy megadott diagram adatcímke százalékérték megjelenítési viselkedését reprezentálja. True esetén megjeleníti, False elrejti. Ír **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerben való gyenge módra való váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívható közvetlenül vagy a [LockContext](../../system/lockcontext/) sentinel objektummal. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IFormattedTextContainer](../iformattedtextcontainer/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)