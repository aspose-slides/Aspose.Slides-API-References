---
title: ErrorBarsFormat
second_title: Aspose.Slides för C++ API-referens
description: "Representerar felstaplar i diagramserie. Anpassade värden för ErrorBars finns i IChartDataPointCollection (i egenskapen IChartDataPoint::get_ErrorBarsCustomValues())."
type: docs
weight: 482
url: /sv/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat klass


Representerar felstaplar i diagramserie. Anpassade värden för ErrorBars finns i [IChartDataPointCollection](../ichartdatapointcollection/) (i egenskapen [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/)).

```cpp
class ErrorBarsFormat : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::ChartSeries>>,
                        public Aspose::Slides::Charts::IErrorBarsFormat
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returnerar det överordnade diagrammet. Skrivskyddad [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Representerar formatet för felstaplarna. Läs [IFormat](../iformat/). |
| **bool** [get_HasEndCap](./get_hasendcap/)() override | Anger att en avslutningskappa inte ritas på felstaplarna. Läs **bool**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Hämtar felstaplarnas synlighet. Läs **bool**. |
| [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() override | Hämtar typ av felstaplar. Läs [ErrorBarType](../errorbartype/). |
| **float** [get_Value](./get_value/)() override | Hämtar värdet som används med värdetyperna Fixed, Percentage och StandardDeviation för att bestämma längden på felstaplarna. I annat fall returneras NaN. Läs **float**. |
| [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() override | Representerar möjliga sätt att bestämma längden på felstaplarna. Vid anpassad värdetyp använder du egenskapen [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) för den specifika datapunkten i DataPoints-samlingen för serien. Vid värdetyperna Fixed, Percentage eller StandardDeviation använder du egenskapen Value för att ange värdet.\n\n Läs [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen inget, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Representerar formatet för felstaplarna. Skriv [IFormat](../iformat/). |
| void [set_HasEndCap](./set_hasendcap/)(**bool**) override | Anger att en avslutningskappa inte ritas på felstaplarna. Skriv **bool**. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Ställer in felstaplarnas synlighet. Skriv **bool**. |
| void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) override | Ställer in typ av felstaplar. Skriv [ErrorBarType](../errorbartype/). |
| void [set_Value](./set_value/)(**float**) override | Ställer in värdet som används med värdetyperna Fixed, Percentage och StandardDeviation för att bestämma längden på felstaplarna. I annat fall returneras NaN. Skriv **float**. |
| void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) override | Representerar möjliga sätt att bestämma längden på felstaplarna. Vid anpassad värdetyp använder du egenskapen [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) för den specifika datapunkten i DataPoints-samlingen för serien. Vid värdetyperna Fixed, Percentage eller StandardDeviation använder du egenskapen Value för att ange värdet.\n\n Skriv [ErrorBarValueType](../errorbarvaluetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ställer in n'te templatarargument till en svag pekare (istället för delad). Gör det möjligt att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning enligt C# lock()-sats för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigir alla interna datastrukturer. |

## Se även

* Klass [DomObject](../../aspose.slides/domobject/)
* Klass [IErrorBarsFormat](../ierrorbarsformat/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)