---
title: IDataLabelFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft formatteringsopties weer voor DataLabel.
type: docs
weight: 963
url: /nl/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat klasse

Geeft formatteringsopties weer voor [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waarde type in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retourneert de grafiek. Alleen-lezen [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Geeft het formaat van het data-label weer. Alleen-lezen [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | Lezen **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | Geeft de formatteerreeks weer voor het DataLabels-object. Lezen [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | Geeft de positie van het data-label weer. Lezen [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | Stelt een Variant in of retourneert deze die het scheidingsteken voor de data-labels op een grafiek vertegenwoordigt. Lezen [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | Geeft het weergeefgedrag van de bubbelgrootte-waarde van een data-label in een specifieke grafiek weer. True toont de bubbelgrootte-waarde. False verbergt deze. Alleen-lezen **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | Geeft het weergeefgedrag van de categorienaam van een data-label in een specifieke grafiek weer. True toont de categorienaam voor de data-labels op een grafiek. False verbergt deze. Alleen-lezen **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | Bepaalt of een data-label van een specifieke grafiek wordt weergegeven als datacommentaar of als data-label. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | Geeft het weergeefgedrag van de celwaarde van een data-label in een specifieke grafiek weer. True toont de celwaarde. False verbergt deze. Alleen-lezen **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | Geeft het weergeefgedrag van de leidende lijnen van een data-label in een specifieke grafiek weer. True toont de leidende lijnen. False verbergt deze. Alleen-lezen **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | Geeft het weergeefgedrag van de legende-sleutel van een data-label in een specifieke grafiek weer. True als de legende-sleutel zichtbaar is. Alleen-lezen **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | Geeft het weergeefgedrag van de percentage-waarde van een data-label in een specifieke grafiek weer. True toont de percentage-waarde. False verbergt deze. Alleen-lezen **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | Retourneert een Boolean om het weergeefgedrag van de serienaam voor de data-labels op een grafiek aan te geven. True om de serienaam te tonen. False om te verbergen. Alleen-lezen **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | Geeft het weergeefgedrag van de percentage-waarde van een data-label in een specifieke grafiek weer. True toont de percentage-waarde. False verbergt deze. Alleen-lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retourneert de basis-slide. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retourneert de tekstindeling van de grafiek. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentietelling-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type dat wordt beschreven door targetType voorstelt. Analoge van de C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, alleen een nieuw object initialiseren en het mogelijk maken om subklassen via copy-constructie te maken. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, alleen een nieuw object initialiseren en het mogelijk maken om subklassen via copy-constructie te maken. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object via referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentietelling met de opgegeven waarde. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | Schrijf **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | Geeft de formatteerreeks weer voor het DataLabels-object. Schrijf [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | Geeft de positie van het data-label weer. Schrijf [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | Stelt een Variant in of retourneert deze die het scheidingsteken voor de data-labels op een grafiek vertegenwoordigt. Schrijf [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | Geeft het weergeefgedrag van de bubbelgrootte-waarde van een data-label in een specifieke grafiek weer. True toont de bubbelgrootte-waarde. False verbergt deze. Schrijf **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | Geeft het weergeefgedrag van de categorienaam van een data-label in een specifieke grafiek weer. True toont de categorienaam voor de data-labels op een grafiek. False verbergt deze. Schrijf **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | Bepaalt of een data-label van een specifieke grafiek wordt weergegeven als datacommentaar of als data-label. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | Geeft het weergeefgedrag van de celwaarde van een data-label in een specifieke grafiek weer. True toont de celwaarde. False verbergt deze. Schrijf **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | Geeft het weergeefgedrag van de leidende lijnen van een data-label in een specifieke grafiek weer. True toont de leidende lijnen. False verbergt deze. Schrijf **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | Geeft het weergeefgedrag van de legende-sleutel van een data-label in een specifieke grafiek weer. True als de legende-sleutel zichtbaar is. Schrijf **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | Geeft het weergeefgedrag van de percentage-waarde van een data-label in een specifieke grafiek weer. True toont de percentage-waarde. False verbergt deze. Schrijf **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | Stelt een Boolean in om het weergeefgedrag van de serienaam voor de data-labels op een grafiek aan te geven. True om de serienaam te tonen. False om te verbergen. Schrijf **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | Geeft het weergeefgedrag van de percentage-waarde van een data-label in een specifieke grafiek weer. True toont de percentage-waarde. False verbergt deze. Schrijf **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in als zwakke pointer (in plaats van gedeelde). Stelt toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentietelling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentietelling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentietelling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentietelling. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |
## Zie ook

* Klasse [IFormattedTextContainer](../iformattedtextcontainer/)
* Namespace [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)