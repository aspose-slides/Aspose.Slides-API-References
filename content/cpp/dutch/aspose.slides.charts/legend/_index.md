---
title: Legend
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de legende-eigenschappen van het diagram voor.
type: docs
weight: 1262
url: /nl/aspose.slides.charts/legend/
---
## Legend klasse

Voorstelt de legende-eigenschappen van het diagram.

```cpp
class Legend : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
               public Aspose::Slides::Charts::ILegend
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Specificeert de werkelijke hoogte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het ophalen van de werkelijke waarden. Lezen **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Specificeert de werkelijke breedte van het grafiekelement. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het ophalen van de werkelijke waarden. Lezen **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Specificeert de werkelijke x-locatie (links) van het grafiekelement ten opzichte van de linkerbovenhoek van het diagram. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het ophalen van de werkelijke waarden. Lezen **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Specificeert de werkelijke bovenkant van het grafiekelement ten opzichte van de linkerbovenhoek van het diagram. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het ophalen van de werkelijke waarden. Lezen **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Onderkant. Alleen-lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retourneert het diagram. Alleen-lezen [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryCollection](../ilegendentrycollection/)\> [get_Entries](./get_entries/)() override | Haalt legende-items op. Alleen-lezen [ILegendEntryCollection](../ilegendentrycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_Entry](./get_entry/)(**int32_t**) override | Haalt eigenschappen op van legende-item dat overeenkomt met datapunt in diagram op de opgegeven index. Bij diagramtypen: staaf-van-taart, uitgesplitste taart, uitgesplitste taart 3D, taart, taart 3D, taart-van-taart, wordt het datapunt genomen uit de eerste serie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Retourneert het formaat van een legende. Alleen-lezen [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Retourneert de hoogte van een legende als een fractie van de diagramhoogte. Lezen **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | Bepaalt of andere diagramonderdelen de legende mogen overlappen. Lezen **bool**. |
| [LegendPositionType](../legendpositiontype/) [get_Position](./get_position/)() override | Specificeert de positie van de legende op een diagram. Niet-NaN waarden van X, Y, Width, Height-eigenschappen overschrijven het effect van deze eigenschap. Lezen [LegendPositionType](../legendpositiontype/). |
| **float** [get_Right](./get_right/)() override | Rechts. Alleen-lezen **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Tekstopmaak. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| **float** [get_Width](./get_width/)() override | Retourneert de breedte van een legende als een fractie van de diagrambreedte. Lezen **float**. |
| **float** [get_X](./get_x/)() override | Retourneert de x-coördinaat van een legende als een fractie van de diagrambreedte. Lezen **float**. |
| **float** [get_Y](./get_y/)() override | Retourneert de y-coördinaat van een legende als een fractie van de diagramhoogte. Lezen **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt het hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie van het type beschrijft dat door targetType wordt omschreven. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert eigenlijk niets, initialiseert alleen nieuw object en maakt kopie-construeren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen nieuw object en maakt kopie-construeren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met opgegeven waarde. |
| void [set_Height](./set_height/)(**float**) override | Stelt de hoogte van een legende in als een fractie van de diagramhoogte. Schrijven **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Bepaalt of andere diagramonderdelen de legende mogen overlappen. Schrijven **bool**. |
| void [set_Position](./set_position/)([LegendPositionType](../legendpositiontype/)) override | Specificeert de positie van de legende op een diagram. Niet-NaN waarden van X, Y, Width, Height-eigenschappen overschrijven het effect van deze eigenschap. Schrijven [LegendPositionType](../legendpositiontype/). |
| void [set_Width](./set_width/)(**float**) override | Stelt de breedte van een legende in als een fractie van de diagrambreedte. Schrijven **float**. |
| void [set_X](./set_x/)(**float**) override | Stelt de x-coördinaat van een legende in als een fractie van de diagrambreedte. Schrijven **float**. |
| void [set_Y](./set_y/)(**float**) override | Stelt de y-coördinaat van een legende in als een fractie van de diagramhoogte. Schrijven **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Stelt n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Bevrijdt alle interne datastructuren. |

## Zie ook

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [ILegend](../ilegend/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)