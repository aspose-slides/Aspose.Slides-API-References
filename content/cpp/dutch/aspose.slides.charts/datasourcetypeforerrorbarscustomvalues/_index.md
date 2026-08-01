---
title: DataSourceTypeForErrorBarsCustomValues
second_title: "Aspose.Slides voor C++ API-referentie"
description: "Specificeert typen van waarden in de eigenschappenlijst van ChartDataPoint::get_ErrorBarsCustomValues"
type: docs
weight: 404
url: /nl/aspose.slides.charts/datasourcetypeforerrorbarscustomvalues/
---
## DataSourceTypeForErrorBarsCustomValues klasse


Specificeert types van waarden in de [ChartDataPoint::get_ErrorBarsCustomValues](../chartdatapoint/get_errorbarscustomvalues/) eigenschappenlijst

```cpp
class DataSourceTypeForErrorBarsCustomValues : public Aspose::Slides::Charts::IDataSourceTypeForErrorBarsCustomValues
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues/)() |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() override | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap feitelijk is in het XMinus-eigenschapobject van datapunten voor aangepaste foutbalkwaarden. Met andere woorden geeft het het type waarde van ChartDataPoint.ErrorBarsCustomValues.XMinus.Data-eigenschap aan. Lees [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() override | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap feitelijk is in het XPlus-eigenschapobject van datapunten voor aangepaste foutbalkwaarden. Met andere woorden geeft het het type waarde van ChartDataPoint.ErrorBarsCustomValues.XPlus.Data-eigenschap aan. Lees [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() override | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap feitelijk is in het YMinus-eigenschapobject van datapunten voor aangepaste foutbalkwaarden. Met andere woorden geeft het het type waarde van ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data-eigenschap aan. Lees [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() override | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap feitelijk is in het YPlus-eigenschapobject van datapunten voor aangepaste foutbalkwaarden. Met andere woorden geeft het het type waarde van ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data-eigenschap aan. Lees [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt hashen van aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat door targetType wordt beschreven. Analoge C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert lock()-statement van C#. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Schakelt klonen van aangepaste typen in. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) override | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap feitelijk is in het XMinus-eigenschapobject van datapunten voor aangepaste foutbalkwaarden. Met andere woorden geeft het het type waarde van ChartDataPoint.ErrorBarsCustomValues.XMinus.Data-eigenschap aan. Schrijf [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) override | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap feitelijk is in het XPlus-eigenschapobject van datapunten voor aangepaste foutbalkwaarden. Met andere woorden geeft het het type waarde van ChartDataPoint.ErrorBarsCustomValues.XPlus.Data-eigenschap aan. Schrijf [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) override | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap feitelijk is in het YMinus-eigenschapobject van datapunten voor aangepaste foutbalkwaarden. Met andere woorden geeft het het type waarde van ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data-eigenschap aan. Schrijf [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) override | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap feitelijk is in het YPlus-eigenschapobject van datapunten voor aangepaste foutbalkwaarden. Met andere woorden geeft het het type waarde van ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data-eigenschap aan. Schrijf [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt de n'th templatesargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge C# [Object.ToString()](../../system/object/tostring/)-methode. Schakelt het converteren van aangepaste objecten naar string in. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [IDataSourceTypeForErrorBarsCustomValues](../idatasourcetypeforerrorbarscustomvalues/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)