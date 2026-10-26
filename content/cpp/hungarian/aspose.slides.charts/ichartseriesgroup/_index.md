---
title: IChartSeriesGroup
second_title: Aspose.Slides for C++ API Referencia
description: A sorozatok csoportját képviseli.
type: docs
weight: 846
url: /hu/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup osztály

A sorozatok csoportját képviseli.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Módszerek

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Meghatározza, hogyan jelennek meg a buborékméret értékek a buborék diagramon. Olvassa [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Meghatározza a buborék diagram skálázási tényezőjét (0 és az alapméret 300%-a között lehet). Olvassa **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Visszaadja a diagramot. Csak olvasásra [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Visszaadja a diagram sorozatot a csoportban a megadott indexnél. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Meghatározza a lyuk méretét a fánk diagramon (10 és 90% között a rajzterület méretéhez képest). Olvassa **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Megkapja az első kördiagram vagy fánk szelet szögét fokban (az órakor irányban fentről, 0-tól 360 fokig). Olvassa **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Visszaadja a távolságot a jelölő szélességének százalékában a 3D diagram adat sorozatai között. Olvassa **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Meghatározza az oszlop vagy sávcsoportok közti távolságot a sáv vagy oszlop szélességének százalékában. Olvassa **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Igaz, ha a diagram sorozatvonalakkal rendelkezik. Alkalmazva halmozott sáv és OfPie diagramokra. Olvassa **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Meghatározza a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal használható. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Meghatározza, hogy a sorozat minden adatjelölője különböző színű legyen. Olvassa **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Meghatározza, mennyire fedjék egymást a sávok és oszlopok 2D diagramokon, százalékban (-100%-tól 100%-ig). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Meghatározza, hogyan kell meghatározni, mely adatpontok vannak a második kör vagy sáv a pie-of-pie vagy bar-of-pie diagramon. Olvassa [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | Az egyedi felosztási információ egy egyéni felosztással rendelkező pie-of-pie vagy bar-of-pie diagramhoz. Visszaadja azt az adatpontot, amelyet a második kör vagy sáv (pie-of-pie vagy bar-of-pie) index alapján kell megrajzolni. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | Az egyéni felosztási információ egy egyéni felosztással rendelkező pie-of-pie vagy bar-of-pie diagramhoz. Tartalmazza a második kör vagy sáv (pie-of-pie vagy bar-of-pie) megjelenítendő adatpontjait. Csak olvasásra [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Meghatározza azt az értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használható. Olvassa **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Jelzi, hogy a csoport sorozatai másodlagos tengelyen vannak-e ábrázolva. Csak olvasásra **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak olvasásra [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Meghatározza a pie-of-pie vagy bar-of-pie diagram második kör vagy sáv méretét az első kör méretének százalékában (5-tól 200%-ig). Olvassa **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Visszaad egy csak olvasásra szánt diagram sorozat-gyűjteményt. Csak olvasásra [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Visszaadja az alap diát. Csak olvasásra [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Visszaadja a sorozatcsoport típusát. Csak olvasásra [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Elérést biztosít a vonal- vagy részvény-diagram fel-/le-sávjaihoz. Csak olvasásra [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Lekéri a megadott indexű elemet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerinti összehasonlítás értéktípusú objektum és nullptr között. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia-számlálót a megadott értékkel. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Meghatározza, hogyan jelennek meg a buborékméret értékek a buborék diagramon. Írja [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Meghatározza a buborék diagram skálázási tényezőjét (0-tól az alapméret 300%-áig). Írja **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Meghatározza a lyuk méretét a fánk diagramon (10-tól 90%-ig a rajzterület méretéhez képest). Írja **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Beállítja az első kör vagy fánk szelet szögét fokban (az órakor irányban fentről, 0-tól 360 fokig). Írja **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Beállítja a távolságot a jelölő szélességének százalékában a 3D diagram adat sorozatai között. Írja **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Meghatározza a sáv vagy oszlop csoportok közti távolságot a sáv vagy oszlop szélességének százalékában. Írja **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Igaz, ha a diagram sorozatvonalakkal rendelkezik. Alkalmazva halmozott sáv és OfPie diagramokra. Írja **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Meghatározza, hogy a sorozat minden adatjelölője különböző színű legyen. Írja **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Meghatározza, mennyire fedjék egymást a sávok és oszlopok 2D diagramokon, százalékban (-100%-tól 100%-ig). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Meghatározza, hogyan kell meghatározni, mely adatpontok vannak a második kör vagy sáv a pie-of-pie vagy bar-of-pie diagramon. Írja [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Meghatározza azt az értéket, amelyet a második kör vagy sáv adatpontjainak meghatározásához használnak pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használható. Írja **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Meghatározza a pie-of-pie vagy bar-of-pie diagram második kör vagy sáv méretét az első kör méretének százalékában (5-tól 200%-ig). Írja **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók tárolókon belüli gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia-számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia-számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia-számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia-számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia-számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

1) Lásd az összefoglalót és a megjegyzéseket a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enum esetén. 2) A sorozatok csoportja néhány sorozat-tulajdonságot tartalmaz, amelyek közösek a csoport minden sorozata számára („series group properties”). A „series group properties” a [ChartSeriesGroup](../chartseriesgroup/) osztályban olvasás-írás. Minden „series group properties” rendelkezhet egy csak-olvasásos vetítéssel a [ChartSeries](../chartseries/) osztályban.

## Lásd még

* Osztály [IChartComponent](../ichartcomponent/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)