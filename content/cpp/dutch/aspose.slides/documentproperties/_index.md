---
title: DocumentProperties
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de eigenschappen van een presentatie voor.
type: docs
weight: 794
url: /nl/aspose.slides/documentproperties/
---
## DocumentProperties klasse


Representeert eigenschappen van een presentatie.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Wis en stel de standaardwaarden in voor alle ingebouwde eigenschappen. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Verwijdert alle aangepaste eigenschappen. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Kloont het huidige object |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Kloont het huidige object |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [DocumentProperties](./documentproperties/)() | Initialiseert een nieuwe instantie van klasse [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van de C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige zwevende-komma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige zwevende-komma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Retourneert het sjabloon van een toepassing. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Retourneert de toepassingsversie. Alleen-lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Retourneert de auteur van een presentatie. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Retourneert de categorie van een presentatie. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Retourneert de opmerkingen van een presentatie. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Retourneert de bedrijfs eigenschap. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Retourneert de inhoudstatus van een presentatie. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Retourneert het inhoudstype van een presentatie. Lezen [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Retourneert het aantal aangepaste eigenschappen dat werkelijk in een collectie aanwezig is. Alleen-lezen **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Retourneert de datum waarop een presentatie is gemaakt. Waarden zijn in UTC. Lezen [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Retourneert het aantal verborgen dia's in een presentatiedocument. Alleen-lezen **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Retourneert de HyperlinkBase-documenteigenschap. Lezen [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Specificeert dat één of meer hyperlinks in dit deel uitsluitend in dit deel door een producent zijn bijgewerkt. De volgende producent die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit deel zijn gespecificeerd. Lezen **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Retourneert de trefwoorden van een presentatie. Lezen [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. Lezen [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Retourneert de naam van de laatste persoon die een presentatie heeft bewerkt. Lezen [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. Waarden zijn in UTC. Alleen-lezen in geval van [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (omdat deze intern wordt bijgewerkt tijdens het opslaan van het [IPresentation](../ipresentation/)-object). Kan worden gewijzigd via de [DocumentProperties](./)-instantie die wordt geretourneerd door de methode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Zie het voorbeeld in de samenvatting van methode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Retourneert de manager-eigenschap. Lezen [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Retourneert het totale aantal geluid- of videoclips dat in het document aanwezig is. Alleen-lezen **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Retourneert de naam van de toepassing. Lezen [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Retourneert het aantal dia's in een presentatie die notities bevatten. Alleen-lezen **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Retourneert het totale aantal alinea's dat in een document is gevonden, indien van toepassing. Alleen-lezen **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Retourneert het beoogde formaat van een presentatie. Lezen [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Retourneert het revisienummer van de presentatie. Lezen **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Geeft de weergavemodus van de document-miniatuur aan. Stel dit element in op **true** om het schalen van de miniatuur naar het beeldscherm in te schakelen. Stel dit element in op **false** om het bijsnijden van de miniatuur in te schakelen zodat alleen secties die op het beeldscherm passen worden getoond. Lezen **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Lezen **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Retourneert het totale aantal dia's in een presentatiedocument. Alleen-lezen **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Retourneert het onderwerp van een presentatie. Lezen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Retourneert de titel van een presentatie. Lezen [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Specificeert de titel van elk documentonderdeel. Deze delen zijn geen documentonderdelen maar conceptuele weergaven van documentsecties. Alleen-lezen [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Totale bewerkingstijd van een presentatie. Lezen [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Retourneert het totale aantal woorden dat in een document staat. Alleen-lezen **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Retourneert een aangepaste eigenschapsnaam op de opgegeven index. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Haalt een benoemde gehele getalwaarde op uit de aangepaste eigenschappen. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Haalt een benoemde tekenreekswaarde op uit de aangepaste eigenschappen. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Hiermee kunnen aangepaste objecten worden gehasht. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Haalt een matrix van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Retourneert de aangepaste eigenschap die aan een opgegeven naam is gekoppeld. Lezen [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Stelt de aangepaste eigenschap in die aan een opgegeven naam is gekoppeld. Schrijf [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Hiermee kunnen aangepaste types worden gekloond. |
| [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert slechts een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Stelt het sjabloon van een toepassing in. Schrijf [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Stelt de auteur van een presentatie in. Schrijf [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Stelt de categorie van een presentatie in. Schrijf [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Stelt de opmerkingen van een presentatie in. Schrijf [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Stelt de bedrijfs eigenschap in. Schrijf [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Stelt de inhoudstatus van een presentatie in. Schrijf [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Stelt het inhoudstype van een presentatie in. Schrijf [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Retourneert de datum waarop een presentatie is gemaakt. Waarden zijn in UTC. Schrijf [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Stelt de HyperlinkBase-documenteigenschap in. Schrijf [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Specificeert dat één of meer hyperlinks in dit deel uitsluitend in dit deel door een producent zijn bijgewerkt. De volgende producent die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit deel zijn gespecificeerd. Schrijf **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Stelt de trefwoorden van een presentatie in. Schrijf [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. Schrijf [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Stelt de naam van de laatste persoon die een presentatie heeft bewerkt in. Schrijf [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. Waarden zijn in UTC. Alleen-lezen in geval van [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (omdat deze intern wordt bijgewerkt tijdens het opslaan van het [IPresentation](../ipresentation/)-object). Kan worden gewijzigd via de [DocumentProperties](./)-instantie die wordt geretourneerd door de methode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Zie het voorbeeld in de samenvatting van methode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Schrijf **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Stelt de manager-eigenschap in. Schrijf [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Stelt de naam van de toepassing in. Schrijf [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Stelt het beoogde formaat van een presentatie in. Schrijf [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Stelt het revisienummer van de presentatie in. Schrijf **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Geeft de weergavemodus van de document-miniatuur aan. Stel dit element in op **true** om het schalen van de miniatuur naar het scherm in te schakelen. Stel dit element in op **false** om het bijsnijden van de miniatuur in te schakelen zodat alleen secties die op het scherm passen worden getoond. Schrijf **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Schrijf **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Stelt het onderwerp van een presentatie in. Schrijf [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Stelt de titel van een presentatie in. Schrijf [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Totale bewerkingstijd van een presentatie. Schrijf [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Stelt een benoemde booleaanse aangepaste eigenschap in. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Stelt een benoemde gehele getalwaarde in. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Stelt een benoemde DateTime aangepaste eigenschap in. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Stelt een benoemde tekenreeks aangepaste eigenschap in. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Stelt een benoemde float aangepaste eigenschap in. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Stelt een benoemde double aangepaste eigenschap in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Hiermee kunnen aangepaste objecten naar een tekenreeks worden geconverteerd. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement voor ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Opmerkingen


Het volgende voorbeeld toont hoe de ingebouwde eigenschappen van PowerPoint [Presentation](../presentation/) kunnen worden benaderd.
```cpp
// Instantieer de Presentation-klasse die de presentatie vertegenwoordigt
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
 Het volgende voorbeeld toont hoe de ingebouwde eigenschappen van PowerPoint [Presentation](../presentation/) kunnen worden aangepast.
```cpp
// Instantieer de Presentation-klasse die de presentatie vertegenwoordigt
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Maak een referentie naar het IDocumentProperties-object dat aan de Presentation is gekoppeld
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Stel de ingebouwde eigenschappen in
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Sla uw presentatie op in een bestand
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [IDocumentProperties](../idocumentproperties/)
* Klasse [IGenericCloneable](../igenericcloneable/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)