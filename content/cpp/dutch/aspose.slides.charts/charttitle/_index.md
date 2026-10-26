---
title: ChartTitle
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt de eigenschappen van de chart-titel.
type: docs
weight: 326
url: /nl/aspose.slides.charts/charttitle/
---
## ChartTitle klasse

Represents chart title properties.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Methoden

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initialiseert TextFrameForOverriding met de tekst in parameter \"text\". Als TextFrameForOverriding al is geïnitialiseerd, wijzigt vervolgens eenvoudigweg zijn tekst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Specificeert de daadwerkelijke hoogte van het chart-element. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lezen **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Specificeert de daadwerkelijke breedte van het chart-element. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lezen **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Specificeert de daadwerkelijke x-locatie (links) van het chart-element relatief ten opzichte van de linkerbovenhoek van de chart. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lezen **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Specificeert de daadwerkelijke bovenkant van het chart-element relatief ten opzichte van de linkerbovenhoek van de chart. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het verkrijgen van de werkelijke waarden. Lezen **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Onderkant. Alleen-lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Geeft de bovenliggende chart terug. Alleen-lezen [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Geeft de opvul-, lijn- en effectstijlen van een titel terug. Alleen-lezen [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Geeft de hoogte van een titel als een fractie van de hoogte van de chart terug. Lezen **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Bepaalt of andere chart-elementen de titel mogen overlappen. Lezen **bool**. |
| **float** [get_Right](./get_right/)() override | Rechts. Alleen-lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Geeft tekstformaat terug. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekstwaarde de automatisch gegenereerde tekst. Automatisch gegenereerde tekst is een impliciete eigenschap van het gegevenslabel, het display-eenheidslabel van de waardas, de as-titel, de chart-titel, het label van de trendlijn. Automatisch gegenereerde tekst wordt opgemaakt met de [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) eigenschap. Alleen-lezen [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Geeft de breedte van een titel als een fractie van de breedte van de chart terug. Lezen **float**. |
| **float** [get_X](./get_x/)() override | Geeft de x-coördinaat van een titel als een fractie van de breedte van de chart terug. Lezen **float**. |
| **float** [get_Y](./get_y/)() override | Geeft de y-coördinaat van een titel als een fractie van de hoogte van de chart terug. Lezen **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Height](./set_height/)(**float**) override | Stelt de hoogte van een titel in als een fractie van de hoogte van de chart. Schrijf **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Bepaalt of andere chart-elementen de titel mogen overlappen. Schrijf **bool**. |
| void [set_Width](./set_width/)(**float**) override | Stelt de breedte van een titel in als een fractie van de breedte van de chart. Schrijf **float**. |
| void [set_X](./set_x/)(**float**) override | Stelt de x-coördinaat van een titel in als een fractie van de breedte van de chart. Schrijf **float**. |
| void [set_Y](./set_y/)(**float**) override | Stelt de y-coördinaat van een titel in als een fractie van de hoogte van de chart. Schrijf **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloon-argument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijmaakt alle interne datastructuren. |

## Zie ook

* Klasse [IChartTitle](../icharttitle/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)