---
title: IErrorBarsFormat
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt foutbalken van grafiekreeksen voor. Aangepaste ErrorBars-waarden bevinden zich in IChartDataPointCollection (in IChartDataPoint::get_ErrorBarsCustomValues() eigenschap)."
type: docs
weight: 1028
url: /nl/aspose.slides.charts/ierrorbarsformat/
---
## IErrorBarsFormat klasse

Stelt foutbalken van een grafiekreeks voor. ErrorBars aangepaste waarden bevinden zich in [IChartDataPointCollection](../ichartdatapointcollection/) (in eigenschap [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/)).

```cpp
class IErrorBarsFormat : public Aspose::Slides::Charts::IChartComponent
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retourneert de grafiek. Alleen-lezen [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Stelt het formaat van de foutbalken voor. Alleen-lezen [IFormat](../iformat/). |
| virtual **bool** [get_HasEndCap](./get_hasendcap/)() | Specificeert dat er geen eindekap wordt getekend op de foutbalken. Alleen-lezen **bool**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | Haalt de zichtbaarheid van foutbalken op. Alleen-lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retourneert de basisdia. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [ErrorBarType](../errorbartype/) [get_Type](./get_type/)() | Haalt het type van foutbalken op. Alleen-lezen [ErrorBarType](../errorbartype/). |
| virtual **float** [get_Value](./get_value/)() | Haalt waarde op die wordt gebruikt met vaste, percentage en standaarddeviatie-waarde types om de lengte van de foutbalken te bepalen. Alleen-lezen **float**. |
| virtual [ErrorBarValueType](../errorbarvaluetype/) [get_ValueType](./get_valuetype/)() | Stelt mogelijke manieren voor om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype om de waarde te specificeren, gebruik de eigenschap [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) van een specifiek gegevenspunt in de DataPoints-collectie van de reeks. 

Alleen-lezen [ErrorBarValueType](../errorbarvaluetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waakhondobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Stelt het formaat van de foutbalken voor. Schrijf [IFormat](../iformat/). |
| virtual void [set_HasEndCap](./set_hasendcap/)(**bool**) | Specificeert dat er geen eindekap wordt getekend op de foutbalken. Schrijf **bool**. |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | Stelt de zichtbaarheid van foutbalken in. Schrijf **bool**. |
| virtual void [set_Type](./set_type/)([ErrorBarType](../errorbartype/)) | Stelt het type van foutbalken in. Schrijf [ErrorBarType](../errorbartype/). |
| virtual void [set_Value](./set_value/)(**float**) | Stelt de waarde in die wordt gebruikt met vaste, percentage en standaarddeviatie-waarde types om de lengte van de foutbalken te bepalen. Schrijf **float**. |
| virtual void [set_ValueType](./set_valuetype/)([ErrorBarValueType](../errorbarvaluetype/)) | Stelt mogelijke manieren voor om de lengte van de foutbalken te bepalen. In het geval van een aangepast waardetype om de waarde te specificeren, gebruik de eigenschap [IChartDataPoint::get_ErrorBarsCustomValues()](../ichartdatapoint/get_errorbarscustomvalues/) van een specifiek gegevenspunt in de DataPoints-collectie van de reeks. 

Schrijf [ErrorBarValueType](../errorbarvaluetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Hiermee kunnen pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert ontgrendeling van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waakhondobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijmaakt alle interne gegevensstructuren. |

## Zie ook

* Klasse [IChartComponent](../ichartcomponent/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)