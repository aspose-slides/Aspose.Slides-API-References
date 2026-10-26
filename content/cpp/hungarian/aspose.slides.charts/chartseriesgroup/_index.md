---
title: ChartSeriesGroup
second_title: Aspose.Slides C++ API hivatkozás
description: A sorozatok csoportját képviseli.
type: docs
weight: 300
url: /hu/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup osztály


A sorozatok csoportját képviseli.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Metódusok

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Megadja, hogyan jelennek meg a buborék méretértékek a buboréktáblázaton. Olvas [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Megadja a buboréktáblázat méretezési tényezőjét (0 és az alapméret 300 százaléka között lehet). Olvas **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Visszaadja a szülő diagramot. Csak olvasható [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Visszaadja a csoportban a megadott indexű diagram sorozatot. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Megadja a fánk diagram lyukjának méretét (0 és a kirajzolási terület méretének 90 százaléka között lehet). Olvas **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Lekéri az első kördiagram vagy fánk diagram szeletének szögét fokban (az órával megegyező irányban fentről, 0 és 360 fok között). Olvas **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Visszaadja a távolságot a jelölő szélességének százalékában a 3D diagram adat sorozatai között. Olvas **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Megadja az oszlop- vagy sávcsoportok közti távolságot a sáv vagy oszlop szélességének százalékában. Olvas **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Igaz, ha a diagramnak sorozatsora van. Alkalmazva a halmozott sáv és OfPie diagramokra. Olvas **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Megadja a HiLowLines formátumot. A HiLowLines a HiLowClose, OpenHiLowClose, VolumeHiLowClose és VolumeOpenHiLowClose diagramtípusokkal együtt alkalmazható. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Megadja, hogy a sorozat minden adatjelzője különböző színű legyen. Olvas **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Megadja, mennyire fedjék egymást a sávok és oszlopok 2-D diagramokon, százalékban (-100 % és 100 % között). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Megadja, hogyan határozzák meg, mely adatpontok vannak a második kördiagramon vagy sávon egy pie-of-pie vagy bar-of-pie diagramon. Olvas [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Az egyéni felosztási információ egy pie-of-pie vagy bar-of-pie diagramhoz egyéni felosztással. Visszaadja azt az adatpontot, amely a második kördiagramon vagy sávon jelenik meg index alapján. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Az egyéni felosztási információ egy pie-of-pie vagy bar-of-pie diagramhoz egyéni felosztással. Az adatpontokat tartalmazza, amelyeket a második kördiagramon vagy sávon kell megjeleníteni. Csak olvasható [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Megadja azt az értéket, amelyet a második kördiagram vagy sáv adatpontjainak meghatározásához használnak egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használatos. Olvas **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Jelzi, hogy a csoport sorozata a másodlagos tengelyen van-e ábrázolva. Csak olvasható **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Megadja a második kördiagram vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, a első kördiagram méretének százalékában (5 és 200 százalék között). Olvas **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Visszaad egy sorozatgyűjteményt. Csak olvasható [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Visszaadja ennek a sorozatcsoportnak a típusát. Csak olvasható [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Nyújt hozzáférést a vonal- vagy részvény-diagram fel-/le-oszlopaihoz. Csak olvasható [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-olását. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Lekéri a megadott indexű elemet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# „is” operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Közvetlenül hívja vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Megadja, hogyan jelennek meg a buborék méretértékek a buboréktáblázaton. Ír [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Megadja a buboréktáblázat méretezési tényezőjét (0 és az alapméret 300 százaléka között). Ír **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Megadja a fánk diagram lyukjának méretét (0 és a rajzterület méretének 90 százalék között). Ír **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Beállítja a szögét az első kör vagy fánk diagram szeletnek fokban (0-tól 360-ig). Ír **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Beállítja a távolságot a jelölő szélességének százalékában a 3D diagram adat sorozatai között. Ír **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Megadja a sáv vagy oszlopcsoportok közti távolságot a sáv vagy oszlop szélességének százalékában. Ír **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Igaz, ha a diagramnak sorozatsora van. Halmozott sáv és OfPie diagramokra alkalmazva. Ír **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Megadja, hogy a sorozat minden adatjelzője különböző színű legyen. Ír **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Megadja, mennyire fedjék egymást a sávok és oszlopok 2-D diagramokon, százalékban (-100 %-tól 100 %-ig). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Megadja, hogyan határozzák meg, mely adatpontok vannak a második kör vagy sáv egy pie-of-pie vagy bar-of-pie diagramon. Ír [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Megadja azt az értéket, amely a második kör vagy sáv adatpontjainak meghatározásához használatos egy pie-of-pie vagy bar-of-pie diagramon. A PieSplitBy tulajdonsággal együtt használva. Ír **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Megadja a második kör vagy sáv méretét egy pie-of-pie vagy bar-of-pie diagramon, az első kör méretének százalékában (5-től 200-ig). Ír **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (nem megosztottra). Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Közvetlenül hívja vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések


1) Lásd az összegzést és a megjegyzéseket a ChartSeriesGroupCollection osztály és a CombinableSeriesTypesGroup enum esetén. 2) A sorozatok csoportja bizonyos sorozat-tulajdonságokat tartalmaz, amelyek közösek a csoport minden sorozata számára („sorozatcsoport-tulajdonságok”). A „sorozatcsoport-tulajdonságok” a [ChartSeriesGroup](./) osztályban olvas-írási jogosultságúak. Minden „sorozatcsoport-tulajdonságnak” lehet csak-olvasható vetülete a [ChartSeries](../chartseries/) osztályban. 

## Lásd még

* Osztály [IChartSeriesGroup](../ichartseriesgroup/)
* Osztály [IDOMObject](../../aspose.slides/idomobject/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)