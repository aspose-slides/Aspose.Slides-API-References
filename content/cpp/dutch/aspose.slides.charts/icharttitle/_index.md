---
title: IChartTitle
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de eigenschappen van de grafiektitel voor.
type: docs
weight: 911
url: /nl/aspose.slides.charts/icharttitle/
---
## IChartTitle klasse

Stelt de eigenschappen van de grafiektitel voor.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initialiseert TextFrameForOverriding met de tekst in parameter \"text\". Als TextFrameForOverriding al is geïnitialiseerd, wordt de tekst eenvoudigweg gewijzigd. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Specificeert de werkelijke hoogte van het chart-element. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het ophalen van werkelijke waarden. Leest **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Specificeert de werkelijke breedte van het chart-element. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het ophalen van werkelijke waarden. Leest **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Specificeert de werkelijke x-locatie (links) van het chart-element relatief ten opzichte van de linkerbovenhoek van de chart. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het ophalen van werkelijke waarden. Leest **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Specificeert de werkelijke bovenkant van het chart-element relatief ten opzichte van de linkerbovenhoek van de chart. Roep methode [IChart::ValidateChartLayout](../ichart/validatechartlayout/) aan vóór het ophalen van werkelijke waarden. Leest **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Haalt de bovenkant van het chart-element op als een fractie van de hoogte van de chart. Alleen-lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retourneert de chart. Alleen-lezen [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Retourneert de vul-, lijn- en effectstijlen van een titel. Alleen-lezen [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Specificeert de hoogte van het chart-element als een fractie van de hoogte van de chart. Leest **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Bepaalt of andere chart-elementen de titel mogen overlappen. Leest **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Haalt de rechterkant van het chart-element op als een fractie van de breedte van de chart. Alleen-lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retourneert de basis-slide. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retourneert het tekstformaat van de chart. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, wordt deze opgemaakte tekstwaarde de automatisch gegenereerde tekst overschreven. Automatisch gegenereerde tekst is een impliciete eigenschap van het gegevenslabel, het weergave-eenheidslabel van de waardenas, de as-titel, de chart-titel, het label van de trendlijn. Automatisch gegenereerde tekst wordt opgemaakt met de [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) eigenschap. Alleen-lezen [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Specificeert de breedte van het chart-element als een fractie van de breedte van de chart. Leest **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Specificeert de x-locatie (links) van het chart-element als een fractie van de breedte van de chart. Leest **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Specificeert de bovenkant van het chart-element als een fractie van de hoogte van de chart. Leest **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object is verbonden. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachter-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, echt, initialiseert enkel een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert enkel een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Specificeert de hoogte van het chart-element als een fractie van de hoogte van de chart. Schrijft **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Bepaalt of andere chart-elementen de titel mogen overlappen. Schrijft **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Specificeert de breedte van het chart-element als een fractie van de breedte van de chart. Schrijft **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Specificeert de x-locatie (links) van het chart-element als een fractie van de breedte van de chart. Schrijft **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Specificeert de bovenkant van het chart-element als een fractie van de hoogte van de chart. Schrijft **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloon-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachter-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijmaakt alle interne datastructuren. |

## Zie ook

* Klasse [ILayoutable](../ilayoutable/)
* Klasse [IOverridableText](../ioverridabletext/)
* Klasse [IActualLayout](../iactuallayout/)
* Namespace [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)