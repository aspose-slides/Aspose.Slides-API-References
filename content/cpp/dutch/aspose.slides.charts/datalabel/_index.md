---
title: DataLabel
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een reeks labels voor.
type: docs
weight: 365
url: /nl/aspose.slides.charts/datalabel/
---
## DataLabel klasse

Stelt een reeks labels voor.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initialiseer TextFrameForOverriding met de tekst in parameter \"text\". Als TextFrameForOverriding al is geïnitialiseerd, wijzigt deze simpelweg de tekst. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | Maakt een nieuw exemplaar van [DataLabel](./) klasse. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Specificeert de werkelijke hoogte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lezen **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Specificeert de werkelijke breedte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lezen **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lezen **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lezen **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Onderkant. Alleen-lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retourneert de bovenliggende grafiek. Alleen-lezen [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | Retourneert het gegevenslabelformaat. Alleen-lezen [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | Retourneert de hoogte van een titel als een fractie van de hoogte van de grafiek. Lezen **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False betekent dat het gegevenslabel niet zichtbaar is (en dus alle Show*-vlaggen (ShowValue, ...) onwaar zijn). Alleen-lezen **bool**. |
| **float** [get_Right](./get_right/)() override | Rechts. Alleen-lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Retourneert tekstformaat. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Kan een rijk opgemaakt tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekstwaarde de automatisch gegenereerde tekst van het gegevenslabel. Automatisch gegenereerde tekst van het gegevenslabel betekent tekst die wordt beheerd door de eigenschappen ShowSeriesName, ShowValue, ... en wordt opgemaakt met de eigenschap TextFormatManager.TextFormat. Alleen-lezen [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | Haalt werkboekdatacel op. Toegepast als de eigenschap IDataLabelFormat::get(set)_ShowLabelValueFromCell waar is. |
| **float** [get_Width](./get_width/)() override | Retourneert de breedte van een titel als een fractie van de breedte van de grafiek. Lezen **float**. |
| **float** [get_X](./get_x/)() override | Retourneert de x-coördinaat van een titel als een fractie van de breedte van de grafiek. Lezen **float**. |
| **float** [get_Y](./get_y/)() override | Retourneert de y-coördinaat van een titel als een fractie van de hoogte van de grafiek. Lezen **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | Retourneert de werkelijke labeltekst op basis van [DataLabelFormat](../datalabelformat/)-instellingen of de waarde van [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text(). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt hashing van aangepaste objecten in staat. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-oproep. |
| void [Hide](./hide/)() override | Verberg het gegevenslabel door alle Show*-vlaggen (ShowValue, ...) op false te zetten. IsVisible zal daarna false zijn. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste typen in staat. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Height](./set_height/)(**float**) override | Stelt de hoogte van een titel in als een fractie van de hoogte van de grafiek. Schrijf **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Stelt werkboekdatacel in. Toegepast als de eigenschap IDataLabelFormat::get(set)_ShowLabelValueFromCell waar is. |
| void [set_Width](./set_width/)(**float**) override | Stelt de breedte van een titel in als een fractie van de breedte van de grafiek. Schrijf **float**. |
| void [set_X](./set_x/)(**float**) override | Stelt de x-coördinaat van een titel in als een fractie van de breedte van de grafiek. Schrijf **float**. |
| void [set_Y](./set_y/)(**float**) override | Stelt de y-coördinaat van een titel in als een fractie van de hoogte van de grafiek. Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Hiermee kan men pointers in containers naar zwakke modus schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt conversie van aangepaste objecten naar string in staat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [IDataLabel](../idatalabel/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)