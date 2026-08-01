---
title: ChartPlotArea
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt een rechthoek waar het diagram moet worden getekend.
type: docs
weight: 248
url: /nl/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea klasse


Represents rectangle where chart should be plotted.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-type-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Specificeert de werkelijke hoogte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) eerst aan om de werkelijke waarden te krijgen. Lees **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Specificeert de werkelijke breedte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) eerst aan om de werkelijke waarden te krijgen. Lees **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van het diagram. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) eerst aan om de werkelijke waarden te krijgen. Lees **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van het diagram. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) eerst aan om de werkelijke waarden te krijgen. Lees **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Onderkant. Alleen-lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Alleen-lezen [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Retourneert het formaat van een plotgebied. Alleen-lezen [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Retourneert de hoogte van een plotgebied-bounding-box als een fractie van de hoogte van het diagram (van 0 tot 1). Lees **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Definieert hoe de locatie moet worden berekend: true \\u2013 automatisch berekend; gedefinieerd door de X, Y, Width, Height-eigenschappen. Alleen-lezen **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Als de lay-out van het plotgebied handmatig is gedefinieerd, specificeert deze eigenschap of het plotgebied moet worden gelayout door de binnenkant (exclusief assen en as-labels) of de buitenkant (inclusief assen en as-labels). Lees [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Rechts. Alleen-lezen **float**. |
| **float** [get_Width](./get_width/)() override | Retourneert de breedte van een plotgebied-bounding-box als een fractie van de breedte van het diagram (van 0 tot 1). Lees **float**. |
| **float** [get_X](./get_x/)() override | Retourneert de x-coördinaat van de linkerbovenhoek van de plotgebied-bounding-box als een fractie van de breedte van het diagram (van 0 tot 1). Lees **float**. |
| **float** [get_Y](./get_y/)() override | Retourneert de y-coördinaat van de linkerbovenhoek van de plotgebied-bounding-box als een fractie van de hoogte van het diagram (van 0 tot 1). Lees **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Verkrijgt de referentieteller-datastructuur die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Verkrijgt het werkelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewaakte object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert slechts een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert slechts een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waarde-type-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Height](./set_height/)(**float**) override | Stelt de hoogte van een plotgebied-bounding-box in als een fractie van de hoogte van het diagram (van 0 tot 1). Schrijf **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Als de lay-out van het plotgebied handmatig is gedefinieerd, specificeert deze eigenschap of het plotgebied moet worden gelayout door de binnenkant (exclusief assen en as-labels) of de buitenkant (inclusief assen en as-labels). Schrijf [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Stelt de breedte van een plotgebied-bounding-box in als een fractie van de breedte van het diagram (van 0 tot 1). Schrijf **float**. |
| void [set_X](./set_x/)(**float**) override | Stelt de x-coördinaat van de linkerbovenhoek van de plotgebied-bounding-box in als een fractie van de breedte van het diagram (van 0 tot 1). Schrijf **float**. |
| void [set_Y](./set_y/)(**float**) override | Stelt de y-coördinaat van de linkerbovenhoek van de plotgebied-bounding-box in als een fractie van de hoogte van het diagram (van 0 tot 1). Schrijf **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Hiermee kunnen pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Verkrijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewaakte object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [IChartPlotArea](../ichartplotarea/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)