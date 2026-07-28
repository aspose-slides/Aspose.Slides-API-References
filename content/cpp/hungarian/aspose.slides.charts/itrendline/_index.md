---
title: ITrendline
second_title: Aspose.Slides for C++ API-referencia
description: Az osztály a diagram sorozat trendvonalát reprezentálja
type: docs
weight: 1223
url: /hu/aspose.slides.charts/itrendline/
---
## ITrendline osztály

Az osztály a diagram sorozat trendvonalát reprezentálja

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Inicializálja a TextFrameForOverriding objektumot a "text" paraméterben megadott szöveggel. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen módosítja a szövegét. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szintaxis használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Ugyanazt a C#-stílusú lebegőpontos összehasonlítást utánozza, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Ugyanazt a C#-stílusú lebegőpontos összehasonlítást utánozza, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **double** [get_Backward](./get_backward/)() | Meghatározza annak a kategóriák (vagy szórt diagram esetén egységek) számát, amelyre a trendvonal a sorozat adatainak elé nyúlik. Szórt és nem szórt diagramok esetén az értéknek nem negatívnak kell lennie. Olvassa **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Visszaadja a diagramot. Csak olvasható [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Megadja, hogy a trendvonal egyenlete megjelenik a diagramon (ugyanabban a címkében, mint az Rsquaredvalue). Olvassa **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Megadja, hogy a trendvonal R-négyzet értéke megjelenik a diagramon (ugyanabban a címkében, mint az egyenlet). Olvassa **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Képviseli a trendvonal formátumát. Olvassa [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Meghatározza annak a kategóriák (vagy szórt diagram esetén egységek) számát, amelyre a trendvonal a sorozat adatainak után nyúlik. Szórt és nem szórt diagramok esetén az értéknek nem negatívnak kell lennie. Olvassa **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Meghatározza azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, linear vagy poly. Olvassa **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Meghatározza a polinomiális trendvonal rendjét. Más trendvonal típusoknál figyelmen kívül marad. Az értéknek 2 és 6 között kell lennie. Olvassa **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Meghatározza a trendvonal periódusát mozgóátlag esetén. Más trendvonal változatoknál figyelmen kívül marad. Az értéknek 2 és 255 között kell lennie. Olvassa **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Visszaadja a prezentációt. Csak olvasható [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Képviseli a legendabejegyzést, amely ehhez a trendvonalhoz kapcsolódik. Csak olvasható [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Visszaadja az alap diát. Csak olvasható [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Visszaadja a diagram szövegformátumát. Csak olvasható [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szöveg felülírja az automatikusan generált szöveget. Az automatikusan generált szöveg egy implicit tulajdonságja az adatcímke, az értéktengely megjelenítési egység címkéje, a tengelycím, a diagramcím, a trendvonal címkéje. Az automatikusan generált szöveget a [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) tulajdonság formázza. Csak olvasható [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Lekéri a trendvonal nevét. Olvassa [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Lekéri a trendvonal típusát. Olvassa [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Tényleg semmit sem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Tényleg semmit sem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hasonlít össze referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a közös referenciaszámlálót a megadott értékkel. |
| virtual void [set_Backward](./set_backward/)(**double**) | Meghatározza annak a kategóriák (vagy szórt diagram esetén egységek) számát, amelyre a trendvonal a sorozat adatainak elé nyúlik. Szórt és nem szórt diagramok esetén az értéknek nem negatívnak kell lennie. Írja **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Megadja, hogy a trendvonal egyenlete megjelenik a diagramon (ugyanabban a címkében, mint az Rsquaredvalue). Írja **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Megadja, hogy a trendvonal R-négyzet értéke megjelenik a diagramon (ugyanabban a címkében, mint az egyenlet). Írja **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Képviseli a trendvonal formátumát. Írja [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Meghatározza annak a kategóriák (vagy szórt diagram esetén egységek) számát, amelyre a trendvonal a sorozat adatainak után nyúlik. Szórt és nem szórt diagramok esetén az értéknek nem negatívnak kell lennie. Írja **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Meghatározza azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, linear vagy poly. Írja **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Meghatározza a polinomiális trendvonal rendjét. Más trendvonal típusoknál figyelmen kívül marad. Az értéknek 2 és 6 között kell lennie. Írja **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Meghatározza a trendvonal periódusát mozgóátlag esetén. Más trendvonal változatoknál figyelmen kívül marad. Az értéknek 2 és 255 között kell lennie. Írja **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Beállítja a trendvonal nevét. Írja [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Beállítja a trendvonal típusát. Írja [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablon argumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a közös referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a közös referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a közös referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) felügyeleti objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IOverridableText](../ioverridabletext/)
* Névterület [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)