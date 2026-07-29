---
title: DataLabelFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar formateringsalternativ för DataLabel.
type: docs
weight: 391
url: /sv/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat klass

Representerar formateringsalternativ för [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Jämför med specificerat objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returnerar diagrammet. Skrivskyddad [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Representerar formatet för dataetiketten. Skrivskyddad [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Läs **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Representerar formatsträngen för DataLabels-objektet. Läs [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Returnerar Parent_Immediate-objektet. Skrivskyddad [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Representerar positionen för dataetiketten. Läs [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Ställer in eller returnerar en Variant som representerar avskiljaren som används för dataetiketter i ett diagram. Läs [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Representerar hur bubbla-storleksvärdet för en specifik diagramdatas etikett visas. True visar bubbla-storleksvärdet. False döljer det. Läs **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Representerar hur kategorinamnet för en specifik diagramdatas etikett visas. True visar kategorinamnet för dataetiketterna i ett diagram. False döljer det. Läs **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Bestämmer om en specifik diagramdatas etikett ska visas som datautrop eller som dataetikett. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Representerar hur cellvärdet för en specifik diagramdatas etikett visas. True visar cellvärdet. False döljer det. Läs **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Representerar hur ledarlinjerna för en specifik diagramdatas etikett visas. True visar ledarlinjerna. False döljer dem. Läs **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Representerar hur legendnyckeln för en specifik diagramdatas etikett visas. True om legendnyckeln är synlig. Läs **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Representerar hur procentvärdet för en specifik diagramdatas etikett visas. True visar procentvärdet. False döljer det. Läs **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Returnerar en Boolean som indikerar hur serienamnet för dataetiketterna i ett diagram visas. True visar serienamnet. False döljer det. Läs **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Representerar hur procentvärdet för en specifik diagramdatas etikett visas. True visar procentvärdet. False döljer det. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Returnerar diagrammets textformat. Skrivskyddad [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Returnerar hash-kod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Skriv **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Representerar formatsträngen för DataLabels-objektet. Skriv [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Representerar positionen för dataetiketten. Skriv [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Ställer in eller returnerar en Variant som representerar avskiljaren som används för dataetiketter i ett diagram. Skriv [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Representerar hur bubbla-storleksvärdet för en specifik diagramdatas etikett visas. True visar bubbla-storleksvärdet. False döljer det. Skriv **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Representerar hur kategorinamnet för en specifik diagramdatas etikett visas. True visar kategorinamnet för dataetiketterna i ett diagram. False döljer det. Skriv **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Bestämmer om en specifik diagramdatas etikett ska visas som datautrop eller som dataetikett. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Representerar hur cellvärdet för en specifik diagramdatas etikett visas. True visar cellvärdet. False döljer det. Skriv **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Representerar hur ledarlinjerna för en specifik diagramdatas etikett visas. True visar ledarlinjerna. False döljer dem. Skriv **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Representerar hur legendnyckeln för en specifik diagramdatas etikett visas. True om legendnyckeln är synlig. Skriv **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Representerar hur procentvärdet för en specifik diagramdatas etikett visas. True visar procentvärdet. False döljer det. Skriv **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Sätt en Boolean som indikerar hur serienamnet för dataetiketterna i ett diagram visas. True visar serienamnet. False döljer det. Skriv **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Representerar hur procentvärdet för en specifik diagramdatas etikett visas. True visar procentvärdet. False döljer det. Skriv **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klass [PVIObject](../../aspose.slides/pviobject/)
* Klass [IDataLabelFormat](../idatalabelformat/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)