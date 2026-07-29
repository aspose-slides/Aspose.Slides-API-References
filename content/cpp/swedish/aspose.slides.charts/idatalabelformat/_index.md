---
title: IDataLabelFormat
second_title: Aspose.Slides för C++ API-referens
description: Representerar formateringsalternativ för DataLabel.
type: docs
weight: 963
url: /sv/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat klass

Representerar formateringsalternativ för [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returnerar diagrammet. Läs-endast [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Representerar formatet för dataetiketten. Läs-endast [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Läs **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Representerar formatsträngen för DataLabels-objektet. Läs [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Representerar positionen för dataetiketten. Läs [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Läs-endast [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Ställer in eller returnerar en Variant som representerar avgränsaren som används för dataetiketter i ett diagram. Läs [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Representerar hur bubbelförstoringsvärdet för en dataetikett i ett specifikt diagram visas. True visar bubbelförstoringsvärdet. False döljer det. Läs **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Representerar hur kategorinamnet för en dataetikett i ett specifikt diagram visas. True för att visa kategorinamnet för dataetiketter i ett diagram. False för att dölja. Läs **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Avgör om en dataetikett i ett specifikt diagram visas som ett datakall eller som en dataetikett. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Representerar hur cellvärdet för en dataetikett i ett specifikt diagram visas. True visar cellvärdet. False döljer det. Läs **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Representerar hur ledande linjer för en dataetikett i ett specifikt diagram visas. True visar ledande linjer. False döljer dem. Läs **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Representerar hur legendnyckeln för en dataetikett i ett specifikt diagram visas. True om legendnyckeln är synlig. Läs **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Representerar hur procentvärdet för en dataetikett i ett specifikt diagram visas. True visar procentvärdet. False döljer det. Läs **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Returnerar en Boolean som anger hur serienamnet för dataetiketter i ett diagram visas. True för att visa serienamnet. False för att dölja. Läs **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Representerar hur procentvärdet för en dataetikett i ett specifikt diagram visas. True visar procentvärdet. False döljer det. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returnerar basissliden. Läs-endast [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Returnerar diagramtextformat. Läs-endast [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-statement låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenräknare med angivet värde. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Skriv **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Representerar formatsträngen för DataLabels-objektet. Skriv [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Representerar positionen för dataetiketten. Skriv [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Ställer in eller returnerar en Variant som representerar avgränsaren som används för dataetiketter i ett diagram. Skriv [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Representerar hur bubbelförstoringsvärdet för en dataetikett i ett specifikt diagram visas. True visar värdet. False döljer det. Skriv **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Representerar hur kategorinamnet för en dataetikett i ett specifikt diagram visas. True för att visa kategorinamnet. False för att dölja. Skriv **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Avgör om en dataetikett i ett specifikt diagram visas som ett datakall eller som en dataetikett. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Representerar hur cellvärdet för en dataetikett i ett specifikt diagram visas. True visar cellvärdet. False döljer det. Skriv **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Representerar hur ledande linjer för en dataetikett i ett specifikt diagram visas. True visar linjerna. False döljer dem. Skriv **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Representerar hur legendnyckeln för en dataetikett i ett specifikt diagram visas. True om den är synlig. Skriv **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Representerar hur procentvärdet för en dataetikett i ett specifikt diagram visas. True visar procentvärdet. False döljer det. Skriv **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Ställer in en Boolean för att ange hur serienamnet för dataetiketter i ett diagram visas. True för att visa serienamnet. False för att dölja. Skriv **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Representerar hur procentvärdet för en dataetikett i ett specifikt diagram visas. True visar procentvärdet. False döljer det. Skriv **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te templateargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referenräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenräknare. Bör inte anropas direkt; använd smartpekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenräknare. Bör inte anropas direkt; använd smartpekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-statement upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenräknare. Bör inte anropas direkt; använd smartpekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenräknare. Bör inte anropas direkt; använd smartpekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [IFormattedTextContainer](../iformattedtextcontainer/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)