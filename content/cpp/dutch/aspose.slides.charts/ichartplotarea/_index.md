---
title: IChartPlotArea
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de eigenschappen van de grafiektitel voor.
type: docs
weight: 794
url: /nl/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea klasse

Stelt de eigenschappen van de grafiektitel voor.

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige vergelijking van zwevende-komma getallen waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige vergelijking van zwevende-komma getallen waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Specificeert de daadwerkelijke hoogte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat u de werkelijke waarden opvraagt. Lees **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Specificeert de daadwerkelijke breedte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat u de werkelijke waarden opvraagt. Lees **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Specificeert de daadwerkelijke x-positie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat u de werkelijke waarden opvraagt. Lees **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Specificeert de daadwerkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van de grafiek. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan voordat u de werkelijke waarden opvraagt. Lees **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Haalt de bovenkant van het grafiekelement op als een fractie van de hoogte van de grafiek. Alleen-lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retourneert de grafiek. Alleen-lezen [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Retourneert het formaat van een plotgebied. Alleen-lezen [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Specificeert de hoogte van het grafiekelement als een fractie van de hoogte van de grafiek. Lees **float**. |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | Als de lay-out van het plotgebied handmatig is gedefinieerd, bepaalt deze eigenschap of het plotgebied wordt gelayout door de binnenkant (exclusief assen en aslabels) of buitenkant (inclusief assen en aslabels). Lees [LayoutTargetType](../layouttargettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Haalt de rechterkant van het grafiekelement op als een fractie van de breedte van de grafiek. Alleen-lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retourneert de basisdia. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Specificeert de breedte van het grafiekelement als een fractie van de breedte van de grafiek. Lees **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Specificeert de x-positie (links) van het grafiekelement als een fractie van de breedte van de grafiek. Lees **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Specificeert de bovenkant van het grafiekelement als een fractie van de hoogte van de grafiek. Lees **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Specificeert de hoogte van het grafiekelement als een fractie van de hoogte van de grafiek. Schrijf **float**. |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | Als de lay-out van het plotgebied handmatig is gedefinieerd, bepaalt deze eigenschap of het plotgebied wordt gelayout door de binnenkant (exclusief assen en aslabels) of buitenkant (inclusief assen en aslabels). Schrijf [LayoutTargetType](../layouttargettype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Specificeert de breedte van het grafiekelement als een fractie van de breedte van de grafiek. Schrijf **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Specificeert de x-positie (links) van het grafiekelement als een fractie van de breedte van de grafiek. Schrijf **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Specificeert de bovenkant van het grafiekelement als een fractie van de hoogte van de grafiek. Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk om aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het unlocken van het C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Zie ook

* Klasse [ILayoutable](../ilayoutable/)
* Klasse [IActualLayout](../iactuallayout/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)