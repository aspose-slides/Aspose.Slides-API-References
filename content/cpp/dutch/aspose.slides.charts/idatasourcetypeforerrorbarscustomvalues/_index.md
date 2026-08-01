---
title: IDataSourceTypeForErrorBarsCustomValues
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert typen van waarden in de lijst met eigenschappen van ChartDataPoint.ErrorBarsCustomValues
type: docs
weight: 976
url: /nl/aspose.slides.charts/idatasourcetypeforerrorbarscustomvalues/
---
## IDataSourceTypeForErrorBarsCustomValues klasse


Specificeert typen van waarden in de lijst met eigenschappen van ChartDataPoint.ErrorBarsCustomValues

```cpp
class IDataSourceTypeForErrorBarsCustomValues : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap werkelijk aanwezig is in het XMinus-eigenschapsobject van datapunten voor aangepaste waarden van foutbalken. Met andere woorden geeft het het type waarde van de eigenschap ChartDataPoint.ErrorBarsCustomValues.XMinus.Data aan. Lees [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap werkelijk aanwezig is in het XPlus-eigenschapsobject van datapunten voor aangepaste waarden van foutbalken. Met andere woorden geeft het het type waarde van de eigenschap ChartDataPoint.ErrorBarsCustomValues.XPlus.Data aan. Lees [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap werkelijk aanwezig is in het YMinus-eigenschapsobject van datapunten voor aangepaste waarden van foutbalken. Met andere woorden geeft het het type waarde van de eigenschap ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data aan. Lees [DataSourceType](../datasourcetype/). |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap werkelijk aanwezig is in het YPlus-eigenschapsobject van datapunten voor aangepaste waarden van foutbalken. Met andere woorden geeft het het type waarde van de eigenschap ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data aan. Lees [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analog van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren via copy construction. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren via copy construction. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap werkelijk aanwezig is in het XMinus-eigenschapsobject van datapunten voor aangepaste waarden van foutbalken. Met andere woorden geeft het het type waarde van de eigenschap ChartDataPoint.ErrorBarsCustomValues.XMinus.Data aan. Schrijf [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap werkelijk aanwezig is in het XPlus-eigenschapsobject van datapunten voor aangepaste waarden van foutbalken. Met andere woorden geeft het het type waarde van de eigenschap ChartDataPoint.ErrorBarsCustomValues.XPlus.Data aan. Schrijf [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap werkelijk aanwezig is in het YMinus-eigenschapsobject van datapunten voor aangepaste waarden van foutbalken. Met andere woorden geeft het het type waarde van de eigenschap ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data aan. Schrijf [DataSourceType](../datasourcetype/). |
| virtual void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap werkelijk aanwezig is in het YPlus-eigenschapsobject van datapunten voor aangepaste waarden van foutbalken. Met andere woorden geeft het het type waarde van de eigenschap ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data aan. Schrijf [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)