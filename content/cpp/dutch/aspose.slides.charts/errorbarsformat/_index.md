---
title: ErrorBarsFormat
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt foutbalken van grafiekreeksen voor. ErrorBars aangepaste waarden zitten in IChartDataPointCollection (in IChartDataPoint::get_ErrorBarsCustomValues() eigenschap)."
type: docs
weight: 482
url: /nl/aspose.slides.charts/errorbarsformat/
---
## ErrorBarsFormat klasse

Stelt foutbalken van een grafiekreeks voor. ErrorBars aangepaste waarden staan in [IChartDataPointCollection](../ichartdatapointcollection/) (in [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) eigenschap).

```cpp
class ErrorBarsFormat : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::ChartSeries>>,
                        public Aspose::Slides::Charts::IErrorBarsFormat
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige floating-point vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige floating-point vergelijking waarbij twee NaN’s als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retourneert de bovenliggende grafiek. Alleen-lezen [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Stelt het formaat van de foutbalken voor. Alleen-lezen [IFormat](../iformat/). |
| **bool** [get_HasEndCap](./get_hasendcap/)() override | Specificeert dat er geen eindkap wordt getekend op de foutbalken. Alleen-lezen **bool**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | Haalt de zichtbaarheid van foutbalken op. Alleen-lezen **bool**. |
| [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() override | Haalt het type van foutbalken op. Alleen-lezen [ErrorBarType](../errorbartype/). |
| **float** [get_Value](./get_value/)() override | Haalt de waarde op die wordt gebruikt met Fixed, Percentage en StandardDeviation waardetypen om de lengte van de foutbalken te bepalen. In alle andere gevallen wordt NaN geretourneerd. Alleen-lezen **float**. |
| [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() override | Stelt mogelijke manieren voor om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype om een waarde op te geven, gebruik de [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) eigenschap van een specifiek datapunten in de DataPoints-collectie van de reeks. In het geval van Fixed, Percentage of StandardDeviation waardetype gebruik de Value-eigenschap om de waarde op te geven.\n\n Alleen-lezen [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep rechtstreeks aan of gebruik [LockContext](../../system/lockcontext/) waarnemingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets werkelijk, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets werkelijk, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Stelt het formaat van de foutbalken voor. Schrijf [IFormat](../iformat/). |
| void [set_HasEndCap](./set_hasendcap/)(**bool**) override | Specificeert dat er geen eindkap op de foutbalken wordt getekend. Schrijf **bool**. |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | Stelt de zichtbaarheid van foutbalken in. Schrijf **bool**. |
| void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) override | Stelt het type van foutbalken in. Schrijf [ErrorBarType](../errorbartype/). |
| void [set_Value](./set_value/)(**float**) override | Stelt de waarde in die wordt gebruikt met Fixed, Percentage en StandardDeviation waardetypen om de lengte van de foutbalken te bepalen. In alle andere gevallen wordt NaN geretourneerd. Schrijf **float**. |
| void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) override | Stelt mogelijke manieren voor om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype om een waarde op te geven, gebruik de [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) eigenschap van een specifiek datapunten in de DataPoints-collectie van de reeks. In het geval van Fixed, Percentage of StandardDeviation waardetype gebruik de Value-eigenschap om de waarde op te geven.\n\n Schrijf [ErrorBarValueType](../errorbarvaluetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Stel het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep rechtstreeks aan of gebruik [LockContext](../../system/lockcontext/) waarnemingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Wis alle interne datastructuren. |

## Zie ook

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [IErrorBarsFormat](../ierrorbarsformat/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)