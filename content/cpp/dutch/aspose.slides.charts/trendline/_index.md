---
title: Trendline
second_title: Aspose.Slides voor C++ API-referentie
description: Klasse vertegenwoordigt de trendlijn van de grafieksreeks
type: docs
weight: 1366
url: /nl/aspose.slides.charts/trendline/
---
## Trendline klasse

Klasse vertegenwoordigt de trendlijn van de grafieksreeks

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initialiseert TextFrameForOverriding met de tekst in parameter "text". Als TextFrameForOverriding al geïnitialiseerd is, verandert dan simpelweg de tekst. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **double** [get_Backward](./get_backward/)() override | Specificeert het aantal categorieën (of eenheden op een spreidingsdiagram) waarmee de trendlijn wordt verlengd vóór de gegevens voor de serie die wordt geanalyseerd. Op spreidings- en niet-spreidingsdiagrammen moet de waarde een niet-negatieve waarde zijn. Read **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retourneert het bovenliggende diagram. Alleen-lezen [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op het diagram (in hetzelfde label als de Rsquaredvalue). Read **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op het diagram (in hetzelfde label als de vergelijking). Read **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Stelt het formaat van de trendlijn voor. Alleen-lezen [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Specificeert het aantal categorieën (of eenheden op een spreidingsdiagram) waarmee de trendlijn wordt verlengd na de gegevens voor de serie die wordt geanalyseerd. Op spreidings- en niet-spreidingsdiagrammen moet de waarde een niet-negatieve waarde zijn. Read **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Specificeert de waarde waar de trendlijn de y-as moet kruisen. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, lineair of poly is. Read **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Specificeert de graad van de polynomiale trendlijn. Het wordt genegeerd voor andere trendlijntypen. Waarde moet tussen 2 en 6 liggen. Read **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde. Het wordt genegeerd voor andere trendlijnvarianten. Waarde moet tussen 2 en 255 liggen. Read **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Stelt de legende-vermelding gerelateerd aan deze trendlijn voor. Alleen-lezen [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Retourneert tekstopmaak. Alleen-lezen [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Kan een rijk opgemaakte tekst bevatten. Als deze eigenschap niet null is, dan overschrijft deze opgemaakte tekstwaarde de automatisch gegenereerde tekst van het gegevenslabel. Automatisch gegenereerde tekst van het gegevenslabel betekent tekst die wordt beheerd door de ShowSeriesName, ShowValue, … eigenschappen en wordt opgemaakt met de TextFormatManager.TextFormat eigenschap. Alleen-lezen [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Haalt de naam van de trendlijn op. Read [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Haalt het type van de trendlijn op. Read [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analog van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waarnemerobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzings-operator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Backward](./set_backward/)(**double**) override | Specificeert het aantal categorieën (of eenheden op een spreidingsdiagram) waarmee de trendlijn wordt verlengd vóór de gegevens voor de serie die wordt geanalyseerd. Op spreidings- en niet-spreidingsdiagrammen moet de waarde een niet-negatieve waarde zijn. Write **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Specificeert dat de vergelijking voor de trendlijn wordt weergegeven op het diagram (in hetzelfde label als de Rsquaredvalue). Write **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Specificeert dat de R-kwadraatwaarde van de trendlijn wordt weergegeven op het diagram (in hetzelfde label als de vergelijking). Write **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Stelt het formaat van de trendlijn voor. Write [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Specificeert het aantal categorieën (of eenheden op een spreidingsdiagram) waarmee de trendlijn wordt verlengd na de gegevens voor de serie die wordt geanalyseerd. Op spreidings- en niet-spreidingsdiagrammen moet de waarde een niet-negatieve waarde zijn. Write **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Specificeert de waarde waar de trendlijn de y-as moet kruisen. Deze eigenschap wordt alleen ondersteund wanneer het trendlijntype exp, lineair of poly is. Write **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Specificeert de graad van de polynomiale trendlijn. Het wordt genegeerd voor andere trendlijntypen. Waarde moet tussen 2 en 6 liggen. Write **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Specificeert de periode van de trendlijn voor een voortschrijdend gemiddelde. Het wordt genegeerd voor andere trendlijnvarianten. Waarde moet tussen 2 en 255 liggen. Write **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Stelt de naam van de trendlijn in. Write [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Stelt het type van de trendlijn in. Write [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat het wisselen van pointers in containers naar zwakke modus toe. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waarnemerobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [DomObject](../../aspose.slides/domobject/)
* Klasse [ITrendline](../itrendline/)
* Namespace [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)