---
title: Trendline
second_title: Aspose.Slides for C++ API referenciája
description: Az osztály a diagram sorozat trendvonalát képviseli
type: docs
weight: 1366
url: /hu/aspose.slides.charts/trendline/
---
## Trendline osztály

Az osztály a diagram sorozat trendvonalát képviseli

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Inicializálja a TextFrameForOverriding-ot a paraméterben megadott \"text\" szöveggel. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen megváltoztatja a szövegét. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintett, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekintett, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **double** [get_Backward](./get_backward/)() override | Meghatározza a kategóriák (vagy szórási diagram esetén egységek) számát, amelyet a trendvonal kiterjeszt a sorozat adatai előtt. Szórási és nem szórási diagramok esetén az érték tetszőleges nem negatív érték lehet. Olvas **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Visszaadja a szülő diagramot. Csak olvasható [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Megadja, hogy a trendvonal egyenlete megjelenik a diagramon (ugyanabban a címkében, mint az Rsquaredvalue). Olvas **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Megadja, hogy a trendvonal R-négyzet értéke megjelenik a diagramon (ugyanabban a címkében, mint az egyenlet). Olvas **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Képviseli a trendvonal formátumát. Olvas [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Meghatározza a kategóriák (vagy szórási diagram egységek) számát, amelyet a trendvonal kiterjeszt az adatok után. Szórási és nem szórási diagramok esetén csak nem negatív értékek megengedettek. Olvas **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Meghadja azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, linear vagy poly. Olvas **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Meghadja a polinomiális trendvonal rendjét. Más trendvonal típusoknál figyelmen kívül hagyott. Az értéknek 2 és 6 között kell lennie. Olvas **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Meghadja a mozgóátlag trendvonal periódusát. Más trendvonal változatoknál figyelmen kívül hagyott. Az értéknek 2 és 255 között kell lennie. Olvas **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Képviseli a legendabejegyzést, amely ehhez a trendvonalhoz tartozik. Csak olvasható [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Visszaadja a szövegformátumot. Csak olvasható [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szövegérték felülírja az automatikusan generált adatcímkét. Az automatikusan generált adatcímke olyan szöveg, amelyet a ShowSeriesName, ShowValue stb. tulajdonságok kezelnek, és a TextFormatManager.TextFormat tulajdonsággal formáznak. Csak olvasható [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Lekéri a trendvonal nevét. Olvas [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Lekéri a trendvonal típusát. Olvas [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_Backward](./set_backward/)(**double**) override | Meghatározza a kategóriák (vagy szórási diagram egységek) számát, amelyet a trendvonal kiterjeszt a sorozat adatai előtt. Szórási és nem szórási diagramok esetén az értéknek nem negatívnak kell lennie. Ír **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Megadja, hogy a trendvonal egyenlete megjelenik a diagramon (ugyanabban a címkében, mint az Rsquaredvalue). Ír **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Megadja, hogy a trendvonal R-négyzet értéke megjelenik a diagramon (ugyanabban a címkében, mint az egyenlet). Ír **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Képviseli a trendvonal formátumát. Ír [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Meghatározza a kategóriák (vagy szórási diagram egységek) számát, amelyet a trendvonal kiterjeszt az adatok után. Szórási és nem szórási diagramok esetén csak nem negatív értékek megengedettek. Ír **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Meghadja azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, linear vagy poly. Ír **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Meghadja a polinomiális trendvonal rendjét. Más trendvonal típusoknál figyelmen kívül hagyott. Az értéknek 2 és 6 között kell lennie. Ír **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Meghadja a mozgóátlag trendvonal periódusát. Más trendvonal változatoknál figyelmen kívül hagyott. Az értéknek 2 és 255 között kell lennie. Ír **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Beállítja a trendvonal nevét. Ír [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Beállítja a trendvonal típusát. Ír [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [DomObject](../../aspose.slides/domobject/)
* Osztály [ITrendline](../itrendline/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)