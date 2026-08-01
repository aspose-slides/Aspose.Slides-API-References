---
title: ChartDataPoint
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een seriedatapunt voor.
type: docs
weight: 144
url: /nl/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint klasse

Stelt een seriedatapunt voor.

```cpp
class ChartDataPoint : public Aspose::Slides::Charts::IChartDataPoint,
                       public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagelijkheid vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagelijkheid vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Specificeert de werkelijke hoogte van het chart-element. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat de werkelijke waarden worden opgehaald. Lees **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Specificeert de werkelijke breedte van het chart-element. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat de werkelijke waarden worden opgehaald. Lees **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Specificeert de werkelijke x-positie (links) van het chart-element relatief ten opzichte van de linkerbovenhoek van de chart. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat de werkelijke waarden worden opgehaald. Lees **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Specificeert de werkelijke bovenkant van het chart-element relatief ten opzichte van de linkerbovenhoek van de chart. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat de werkelijke waarden worden opgehaald. Lees **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() override | BubbleSize. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() override | Geeft de kleurwaarde van het chart-datapunt terug. Wordt gebruikt met Map-charts. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) override | Geeft een datapuntniveau op de opgegeven index terug. Toegepast voor Treeamp- en Sunburst-reeksen. Indexering van datapuntniveaus begint bij nul. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() override | Geeft de container van datapuntniveaus terug. Toegepast voor Treeamp- en Sunburst-reeksen. Indexering van datapuntniveaus begint bij nul. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() override | Stelt waarden van serie-foutbalken voor in het geval van een Custom-valuetype. Alleen-lezen [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| **int32_t** [get_Explosion](./get_explosion/)() override | Specificeert de hoeveelheid waarmee het datapunt van het middelpunt van de taart wordt verplaatst. Lees **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Stelt de opmaak-eigenschappen voor. Lees [IFormat](../iformat/). |
| **uint32_t** [get_Index](./get_index/)() override | Bepaalt tot welke collectie van kindobjecten van de ouder dit datapunt behoort. Lees **uint32_t**. |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | Specificeert dat het datapunt zijn kleuren moet omkeren als de waarde negatief is. Lees **bool**. |
| **bool** [get_IsBubble3D](./get_isbubble3d/)() override | Specificeert dat de bubbels een 3-D-effect hebben. Lees **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() override | Label. Alleen-lezen [IDataLabel](../idatalabel/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | Specificeert een datamarker. Alleen-lezen [IMarker](../imarker/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Eigenschappen van het overeenkomende legendagegeven in het geval van een chart-type uit deze lijst: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). Alleen-lezen [ILegendEntryProperties](../ilegendentryproperties/). |
| **bool** [get_SetAsTotal](./get_setastotal/)() override | Stelt het datapunt in als totaal. Alleen toegepast voor Waterfall-reeks. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() override | Geeft de groottewaarde van het chart-datapunt terug. Wordt gebruikt met Treemap- en Sunburst-charts. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() override | Waarde. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() override | XValue. Alleen-lezen [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() override | YValue. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() override | Geeft een automatische kleur van het datapunt terug gebaseerd op series-index, datapunt-index, ParentSeriesGroup.IsColorVaried-eigenschap en chart-stijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het actuele type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentry-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignatie-operator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| void [Remove](./remove/)() override | Verwijdert DataPoint uit chart-reeks. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | Specificeert de hoeveelheid waarmee het datapunt van het midden van de taart wordt verplaatst. Schrijf **int32_t**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Stelt de opmaak-eigenschappen voor. Schrijf [IFormat](../iformat/). |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | Specificeert dat het datapunt zijn kleuren moet omkeren als de waarde negatief is. Schrijf **bool**. |
| void [set_IsBubble3D](./set_isbubble3d/)(**bool**) override | Specificeert dat de bubbels een 3-D-effect hebben. Schrijf **bool**. |
| void [set_SetAsTotal](./set_setastotal/)(**bool**) override | Stelt het datapunt in als totaal. Alleen toegepast voor Waterfall-reeks. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-template-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct aangeroepen worden; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct aangeroepen worden; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentry-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct aangeroepen worden; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct aangeroepen worden; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IChartDataPoint](../ichartdatapoint/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)