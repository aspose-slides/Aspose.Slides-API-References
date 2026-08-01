---
title: IDoubleChartValue
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een double-waarde voor die op twee manieren in een pptx-presentatiedocument kan worden opgeslagen: 1) in cel/cellen van een werkmap die gerelateerd is aan de grafiek; 2) als letterlijke waarde."
type: docs
weight: 1002
url: /nl/aspose.slides.charts/idoublechartvalue/
---
## IDoubleChartValue klasse


Stelt een double-waarde voor die in een pptx-presentatiedocument op twee manieren kan worden opgeslagen: 1) in cel/cellen van een werkmap gerelateerd aan de grafiek; 2) als letterlijke waarde.

```cpp
class IDoubleChartValue : public Aspose::Slides::Charts::ISingleCellChartValue
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel NaN volgens IEC 60559:1989 niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl floating-point-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel NaN volgens IEC 60559:1989 niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_AsCell](../isinglecellchartvalue/get_ascell/)() | Retourneert grafiek-datacel. Lees [IChartDataCell](../ichartdatacell/). |
| virtual **double** [get_AsLiteralDouble](./get_asliteraldouble/)() | Retourneert letterlijke double-waarde indien DataSourceType = [Charts::DataSourceType::DoubleLiterals](../datasourcetype/). Lees **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Data](../ibasechartvalue/get_data/)() |  |
| virtual [Aspose::Slides::Charts::DataSourceType](../datasourcetype/) [get_DataSourceType](../ibasechartvalue/get_datasourcetype/)() | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap actief is. Met andere woorden specificeert het het type waarde van de Data-eigenschap. Deze eigenschap is alleen-lezen. Om de waarde van deze eigenschap te wijzigen kun je een van de ChartDataPointCollection.DataSourceTypeFor<...>-eigenschappen gebruiken. Lees [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert lock()-statement-vergrendeling van C#. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewaakobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() |  |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AsCell](../isinglecellchartvalue/set_ascell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Stelt de grafiek-datacel in. Schrijf [IChartDataCell](../ichartdatacell/). |
| virtual void [set_AsLiteralDouble](./set_asliteraldouble/)(**double**) | Stelt de letterlijke double-waarde in indien DataSourceType = [Charts::DataSourceType::DoubleLiterals](../datasourcetype/). Schrijf **double**. |
| virtual void [set_Data](../ibasechartvalue/set_data/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) |  |
| virtual void [set_DataSourceType](../ibasechartvalue/set_datasourcetype/)([Aspose::Slides::Charts::DataSourceType](../datasourcetype/)) | Specificeert of de AsCell- of AsLiteralString- of AsLiteralDouble-eigenschap actief is. Met andere woorden specificeert het het type waarde van de Data-eigenschap. Deze eigenschap is alleen-lezen. Om de waarde van deze eigenschap te wijzigen kun je een van de ChartDataPointCollection.DataSourceTypeFor<...>-eigenschappen gebruiken. Schrijf [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Hiermee kun je pointers in containers naar zwakke modus schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde op van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual **double** [ToDouble](./todouble/)() | Converteert naar double. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert lock()-statement-ontgrendeling van C#. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewaakobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [ISingleCellChartValue](../isinglecellchartvalue/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)