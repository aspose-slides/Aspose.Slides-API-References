---
title: IDocumentProperties
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de eigenschappen van een presentatie voor.
type: docs
weight: 1977
url: /nl/aspose.slides/idocumentproperties/
---
## IDocumentProperties klasse

Stelt de eigenschappen van een presentatie voor.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Wis en stelt standaardwaarden in voor alle ingebouwde eigenschappen. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Verwijdert alle aangepaste eigenschappen. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Controleert aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al volgens IEC 60559:1989 is NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Retourneert de sjabloon van een toepassing. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Retourneert de toepassingsversie. Alleen-lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Retourneert de auteur van een presentatie. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Retourneert de categorie van een presentatie. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Retourneert de opmerkingen van een presentatie. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Retourneert de bedrijfs-eigenschap. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Retourneert de inhoudstatus van een presentatie. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Retourneert het inhoudstype van een presentatie. Lezen [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Retourneert het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie aanwezig is. Alleen-lezen **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Retourneert de datum waarop een presentatie is aangemaakt. Waarden zijn in UTC. Lezen [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Specificeert het aantal verborgen dia's in een presentatiedocument. Alleen-lezen **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Retourneert de HyperlinkBase documenteigenschap. Lezen [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Specificeert dat één of meer hyperlinks in dit deel exclusief in dit deel door een producent zijn bijgewerkt. De volgende producent die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit deel zijn gespecificeerd. Lezen **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Retourneert de trefwoorden van een presentatie. Lezen [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. Lezen [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Retourneert de naam van de laatst persoon die een presentatie heeft gewijzigd. Lezen [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. Waarden zijn in UTC.P Alleen-lezen in het geval van Presentation.DocumentProperties (omdat het intern wordt bijgewerkt tijdens het [IPresentation](../ipresentation/)-object-opslaan-proces). Kan worden gewijzigd via de [DocumentProperties](../documentproperties/)-instantie die wordt geretourneerd door de methode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Zie het voorbeeld in de samenvatting van de methode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Retourneert de manager-eigenschap. Lezen [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Specificeert het totale aantal audio- of videoclips dat in het document aanwezig is. Alleen-lezen **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Retourneert de naam van de toepassing. Lezen [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Specificeert het aantal dia's in een presentatie die notities bevatten. Alleen-lezen **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Specificeert het totale aantal alinea's dat in een document is gevonden, indien van toepassing. Alleen-lezen **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Retourneert het beoogde formaat van een presentatie. Lezen [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Retourneert het revisienummer van de presentatie. Lezen **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om schaling van de miniatuur naar de weergave mogelijk te maken. Stel dit element in op **false** om bijsnijden van de miniatuur mogelijk te maken zodat alleen delen getoond worden die op de weergave passen. Lezen **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Lezen **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Specificeert het totale aantal dia's in een presentatiedocument. Alleen-lezen **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Retourneert het onderwerp van een presentatie. Lezen [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Retourneert de titel van een presentatie. Lezen [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Specificeert de titel van elk documentonderdeel. Deze delen zijn geen documentonderdelen maar conceptuele representaties van documentsecties. Alleen-lezen [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Totale bewerkingstijd van een presentatie. Lezen [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Specificeert het totale aantal woorden dat in een document voorkomt. Alleen-lezen **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Retourneert een aangepaste eigenschapsnaam op de opgegeven index. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Haalt een benoemde geheel-getalwaarde op uit de aangepaste eigenschappen. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Haalt een benoemde tekenreekswaarde op uit de aangepaste eigenschappen. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Haalt een array van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK-metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Retourneert de aangepaste eigenschap die aan een opgegeven naam is gekoppeld. Lezen [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Stelt de aangepaste eigenschap in die aan een opgegeven naam is gekoppeld. Schrijf [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of een object een instantie is van het type dat door targetType wordt beschreven. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentietype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Stelt de sjabloon van een toepassing in. Schrijf [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Stelt de auteur van een presentatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Stelt de categorie van een presentatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Stelt de opmerkingen van een presentatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Stelt de bedrijfs-eigenschap in. Schrijf [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Stelt de inhoudstatus van een presentatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Stelt het inhoudstype van een presentatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Retourneert de datum waarop een presentatie is aangemaakt. Waarden zijn in UTC. Schrijf [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Stelt de HyperlinkBase-documenteigenschap in. Schrijf [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Specificeert dat één of meer hyperlinks in dit deel exclusief in dit deel door een producent zijn bijgewerkt. De volgende producent die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit deel zijn gespecificeerd. Schrijf **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Stelt de trefwoorden van een presentatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. Schrijf [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Stelt de naam van de laatste persoon die een presentatie heeft gewijzigd in. Schrijf [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. Waarden zijn in UTC.P Alleen-lezen in geval van Presentation.DocumentProperties (omdat het intern wordt bijgewerkt tijdens het [IPresentation](../ipresentation/)-object-opslaan-proces). Kan worden gewijzigd via [DocumentProperties](../documentproperties/)-instantie die wordt geretourneerd door de methode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Zie het voorbeeld in de samenvatting van de methode [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Schrijf **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Stelt de manager-eigenschap in. Schrijf [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Stelt de naam van de toepassing in. Schrijf [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Stelt het beoogde formaat van een presentatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Stelt het revisienummer van de presentatie in. Schrijf **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om schaling van de miniatuur naar de weergave mogelijk te maken. Stel dit element in op **false** om bijsnijden van de miniatuur mogelijk te maken zodat alleen delen getoond worden die op de weergave passen. Schrijf **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Schrijf **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Stelt het onderwerp van een presentatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Stelt de titel van een presentatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Totale bewerkingstijd van een presentatie. Schrijf [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Stelt een benoemde booleaanse aangepaste eigenschap in. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Stelt een benoemde gehele aangepaste eigenschap in. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Stelt een benoemde DateTime-aangepaste eigenschap in. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Stelt een benoemde tekenreeks-aangepaste eigenschap in. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Stelt een benoemde float-aangepaste eigenschap in. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Stelt een benoemde double-aangepaste eigenschap in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar tekenreeks mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)