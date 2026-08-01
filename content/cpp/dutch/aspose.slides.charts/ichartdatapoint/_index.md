---
title: IChartDataPoint
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een seriedatapunt voor.
type: docs
weight: 677
url: /nl/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint klasse

Stelt een seriedatapunt voor.

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert een C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert een C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Specificeert de werkelijke hoogte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lees **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Specificeert de werkelijke breedte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lees **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lees **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lees **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | Geeft de bubbelformaat van het grafiekdatapunt terug. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | Geeft de kleurwaarde van het grafiekdatapunt terug. Wordt gebruikt met kaartgrafieken. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | Geeft een datapuntniveau op de opgegeven index terug. Toegepast voor Treeamp- en Sunburst-series. Indexering van datapuntniveaus begint bij nul. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | Geeft de container van datapuntniveaus terug. Toegepast voor Treeamp- en Sunburst-series. Indexering van datapuntniveaus begint bij nul. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | Stelt de waarden van foutenbalken van de serie voor in het geval van een aangepast waarde-type. Alleen-lezen [IErrorBarsCustomValues](../ierrorbarscustomvalues/). |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | Specificeert de hoeveelheid waarmee het datapunt vanuit het middelpunt van de taart moet worden verplaatst. Lees **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Stelt de opmaak-eigenschappen voor. Lees [IFormat](../iformat/). |
| virtual **uint32_t** [get_Index](./get_index/)() | Bepaalt tot welke van de kindcollecties van de ouder dit datapunt behoort. Lees **uint32_t**. |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | Specificeert dat het datapunt zijn kleuren moet omkeren als de waarde negatief is. Lees **bool**. |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | Specificeert dat de bubbels een 3-D-effect hebben. Lees **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | Stelt het label van het grafiekdatapunt voor. Alleen-lezen [IDataLabel](../idatalabel/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | Specificeert een datamarker. Alleen-lezen [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Eigenschappen van de overeenkomstige legende-vermelding in het geval van grafiektype uit deze lijst: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/). Alleen-lezen [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | Stelt het datapunt in als totaal. Alleen van toepassing op Waterfall-series. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | Geeft de groottewaarde van het grafiekdatapunt terug. Wordt gebruikt met Treemap- en Sunburst-grafieken. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | Geeft de waarde van het grafiekdatapunt terug. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | Geeft de x-waarde van het grafiekdatapunt terug. Alleen-lezen [IStringOrDoubleChartValue](../istringordoublechartvalue/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | Geeft de y-waarde van het grafiekdatapunt terug. Alleen-lezen [IDoubleChartValue](../idoublechartvalue/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | Geeft een automatische kleur van datapunt terug op basis van series-index, datapunt-index, ParentSeriesGroup.IsColorVaried-eigenschap en grafiekstijl. Deze kleur wordt standaard gebruikt als FillType gelijk is aan NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Staat hashing van aangepaste objecten toe. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Staat het klonen van aangepaste types toe. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructeur. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| virtual void [Remove](./remove/)() | Verwijdert DataPoint uit de grafiekserie. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | Specificeert de hoeveelheid waarmee het datapunt vanaf het middelpunt van de taart moet worden verplaatst. Schrijf **int32_t**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Stelt de opmaak-eigenschappen voor. Schrijf [IFormat](../iformat/). |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | Specificeert dat het datapunt zijn kleuren moet omkeren als de waarde negatief is. Schrijf **bool**. |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | Specificeert dat de bubbels een 3-D-effect hebben. Schrijf **bool**. |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | Stelt het datapunt in als totaal. Alleen van toepassing op Waterfall-series. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-sjabloonargument in op een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Staat conversie van aangepaste objecten naar string toe. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentinel-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IActualLayout](../iactuallayout/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)