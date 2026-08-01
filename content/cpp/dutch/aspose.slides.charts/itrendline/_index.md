---
title: ITrendline
second_title: Aspose.Slides voor C++ API-referentie
description: Klasse vertegenwoordigt trendlijn van grafiekserie
type: docs
weight: 1223
url: /nl/aspose.slides.charts/itrendline/
---
## ITrendline klasse

Klasse vertegenwoordigt de trendlijn van de grafiekserie

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Methoden

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initialiseert TextFrameForOverriding met de tekst in parameter \"text\". Als TextFrameForOverriding al is geïnitialiseerd, verandert dan gewoon de tekst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert zwevendkommagelijk vergelijking in C#-stijl waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert zwevendkommagelijk vergelijking in C#-stijl waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual **double** [get_Backward](./get_backward/)() | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrand. Op spreidings- en niet-spreidingsgrafieken moet de waarde elke niet-negatieve waarde zijn. Lezen **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Retourneert de grafiek. Alleen-lezen [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredvalue). Lezen **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). Lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Vertegenwoordigt het formaat van de trendlijn. Lezen [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrand. Op spreidings- en niet-spreidingsgrafieken moet de waarde elke niet-negatieve waarde zijn. Lezen **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Specificeert de waarde waar de trendlijn de y-as moet kruisen. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, lineair of poly is. Lezen **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Specificeert de graad van de polynomiale trendlijn. Het wordt genegeerd voor andere trendlijntypes. De waarde moet tussen 2 en 6 liggen. Lezen **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde trendlijn. Het wordt genegeerd voor andere trendlijnvarianten. De waarde moet tussen 2 en 255 liggen. Lezen **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Retourneert de presentatie. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Vertegenwoordigt legendavermelding gerelateerd aan deze trendlijn Alleen-lezen [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Retourneert de basisslide. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Retourneert grafiekttekstformaat. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, overschrijft deze opgemaakte tekstwaarde de automatisch gegenereerde tekst. Automatisch gegenereerde tekst is een impliciete eigenschap van het gegevenslabel, het weergave-eenheidlabel van de waardas, de as-titel, de grafiektitel, het label van de trendlijn. Automatisch gegenereerde tekst wordt geformatteerd met de [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) eigenschap. Alleen-lezen [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Haalt de naam van de trendlijn op. Lezen [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Haalt het type van de trendlijn op. Lezen [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type beschrijft dat door targetType wordt aangegeven. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachto-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiërende constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiewaarde van een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_Backward](./set_backward/)(**double**) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt vóór de gegevens voor de serie die wordt getrand. Op spreidings- en niet-spreidingsgrafieken moet de waarde elke niet-negatieve waarde zijn. Schrijven **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de Rsquaredvalue). Schrijven **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op de grafiek (in hetzelfde label als de vergelijking). Schrijven **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Vertegenwoordigt het formaat van de trendlijn. Schrijven [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Specificeert het aantal categorieën (of eenheden op een spreidingsgrafiek) dat de trendlijn zich uitstrekt na de gegevens voor de serie die wordt getrand. Op spreidings- en niet-spreidingsgrafieken moet de waarde elke niet-negatieve waarde zijn. Schrijven **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Specificeert de waarde waar de trendlijn de y-as moet kruisen. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, lineair of poly is. Schrijven **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Specificeert de graad van de polynomiale trendlijn. Het wordt genegeerd voor andere trendlijntypes. De waarde moet tussen 2 en 6 liggen. Schrijven **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde trendlijn. Het wordt genegeerd voor andere trendlijnvarianten. De waarde moet tussen 2 en 255 liggen. Schrijven **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Stelt de naam van de trendlijn in. Schrijven [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Stelt het type van de trendlijn in. Schrijven [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachto-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne gegevensstructuren. |
## Zie ook

* Class [IOverridableText](../ioverridabletext/)
* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)