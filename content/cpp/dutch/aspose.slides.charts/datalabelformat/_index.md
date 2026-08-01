---
title: DataLabelFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de opmaakopties voor DataLabel voor.
type: docs
weight: 391
url: /nl/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat klasse


Stelt opmaakopties voor [DataLabel](../datalabel/) voor.

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergelijkt met het opgegeven object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retourneert de grafiek. Alleen-lezen [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Stelt het formaat van het gegevenslabel voor. Alleen-lezen [IFormat](../iformat/). |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | Leest **bool**. |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | Stelt de opmaakreeks voor het DataLabels-object voor. Leest [System::String](../../system/string/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate-object. Alleen-lezen [IDOMObject](../../aspose.slides/idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | Retourneert ouder [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | Stelt de positie van het gegevenslabel voor. Leest [LegendDataLabelPosition](../legenddatalabelposition/). |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | Stelt een Variant in of retourneert deze die de scheidingsteken voor de gegevenslabels op een grafiek vertegenwoordigt. Leest [System::String](../../system/string/). |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | Stelt het weergavegedrag van de bubbelgroottewaarde van het gegevenslabel van een opgegeven grafiek voor. Waar (true) toont de bubbelgroottewaarde. Onwaar (false) verbergt deze. Leest **bool**. |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. Waar toont de categorienaam. Onwaar verbergt deze. Leest **bool**. |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | Bepaalt of het gegevenslabel van de opgegeven grafiek wordt weergegeven als gegevensbijschrift of als gegevenslabel. |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | Stelt het weergavegedrag van de celwaarde van het gegevenslabel van een opgegeven grafiek voor. Waar toont de celwaarde. Onwaar verbergt deze. Leest **bool**. |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | Stelt het weergavegedrag van de leiderlijnen van het gegevenslabel van een opgegeven grafiek voor. Waar toont de leiderlijnen. Onwaar verbergt ze. Leest **bool**. |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | Stelt het weergavegedrag van de legende-sleutel van het gegevenslabel van een opgegeven grafiek voor. Waar als de legende-sleutel zichtbaar is. Leest **bool**. |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | Stelt het weergavegedrag van de percentwaarde van het gegevenslabel van een opgegeven grafiek voor. Waar toont de percentwaarde. Onwaar verbergt deze. Leest **bool**. |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | Retourneert een Boolean die aangeeft hoe de serienaam van de gegevenslabels op een grafiek wordt weergegeven. Waar om de serienaam te tonen. Onwaar om te verbergen. Leest **bool**. |
| **bool** [get_ShowValue](./get_showvalue/)() override | Stelt het weergavegedrag van de percentwaarde van het gegevenslabel van een opgegeven grafiek voor. Waar toont de percentwaarde. Onwaar verbergt deze. Leest **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Retourneert het tekstformaat van de grafiek. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object verbonden is. |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | Retourneert hash-code. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waakhondobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, maar initialiseert een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | Schrijf **bool**. |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | Stelt de opmaakreeks voor het DataLabels-object voor. Schrijf [System::String](../../system/string/). |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | Stelt de positie van het gegevenslabel voor. Schrijf [LegendDataLabelPosition](../legenddatalabelposition/). |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | Stelt een Variant in of retourneert deze die de scheidingsteken voor de gegevenslabels op een grafiek vertegenwoordigt. Schrijf [System::String](../../system/string/). |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | Stelt het weergavegedrag van de bubbelgroottewaarde van het gegevenslabel van een opgegeven grafiek voor. Waar toont de bubbelgroottewaarde. Onwaar verbergt deze. Schrijf **bool**. |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | Stelt het weergavegedrag van de categorienaam van het gegevenslabel van een opgegeven grafiek voor. Waar toont de categorienaam. Onwaar verbergt deze. Schrijf **bool**. |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | Bepaalt of het gegevenslabel van de opgegeven grafiek wordt weergegeven als gegevensbijschrift of als gegevenslabel. |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | Stelt het weergavegedrag van de celwaarde van het gegevenslabel van een opgegeven grafiek voor. Waar toont de celwaarde. Onwaar verbergt deze. Schrijf **bool**. |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | Stelt het weergavegedrag van de leiderlijnen van het gegevenslabel van een opgegeven grafiek voor. Waar toont de leiderlijnen. Onwaar verbergt deze. Schrijf **bool**. |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | Stelt het weergavegedrag van de legende-sleutel van het gegevenslabel van een opgegeven grafiek voor. Waar als de legende-sleutel zichtbaar is. Schrijf **bool**. |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | Stelt het weergavegedrag van de percentwaarde van het gegevenslabel van een opgegeven grafiek voor. Waar toont de percentwaarde. Onwaar verbergt deze. Schrijf **bool**. |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | Stelt een Boolean in om het weergavegedrag van de serienaam voor de gegevenslabels op een grafiek aan te geven. Waar om de serienaam te tonen. Onwaar om te verbergen. Schrijf **bool**. |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | Stelt het weergavegedrag van de percentwaarde van het gegevenslabel van een opgegeven grafiek voor. Waar toont de percentwaarde. Onwaar verbergt deze. Schrijf **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt de gedeelde referentieteller en retourneert deze. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk om aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waakhondobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijmaakt alle interne datastructuren. |
## Zie ook

* Klasse [PVIObject](../../aspose.slides/pviobject/)
* Klasse [IDataLabelFormat](../idatalabelformat/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)