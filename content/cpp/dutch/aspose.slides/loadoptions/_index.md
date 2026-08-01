---
title: LoadOptions
second_title: Aspose.Slides voor C++ API Referentie
description: Stelt extra opties (zoals formaat of standaardlettertype) in bij het laden van een presentatie.
type: docs
weight: 4395
url: /nl/aspose.slides/loadoptions/
---
## LoadOptions klasse


Allows to specify additional options (such as format or default font) when loading a presentation.

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert een C#-stijl drijvende-kommagelijk vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert een C#-stijl drijvende-kommagelijk vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | Stelt de opties voor die kunnen worden gebruikt om het gedrag van Binary Large Objects (BLOBs) te beheren, zoals het gebruik van tijdelijke bestanden of maximaal aantal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste verhouding tussen prestaties en geheugengebruik te realiseren voor een specifieke omgeving of vereisten. |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | Retourneert het Aziatische lettertype dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Zie [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | Retourneert het reguliere lettertype dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Zie [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | Retourneert het symboollettertype dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Zie [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | Retourneert de standaardtaal voor de presentatie-tekst. Zie [System::String](../../system/string/). |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | Bepaalt of [Aspose.Slides](../) alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | Het token om onderbrekingsverzoeken te monitoren. |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | Retourneert het formaat van een te laden presentatie. Zie [Slides::LoadFormat](../loadformat/). |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | Deze eigenschap is relevant als het presentatiebestand met een wachtwoord is beveiligd. De waarde true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld presentatiebestand en dat het wachtwoord moet worden genegeerd. De waarde false betekent dat de volledige versleutelde presentatie moet worden geladen met gebruik van het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd. Als documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid. Zie **bool**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Haalt het wachtwoord op. Zie [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | Retourneert de callback-interface die het laden van externe bronnen beheert. Zie [IResourceLoadingCallback](../iresourceloadingcallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | Haalt opties op voor spreadsheets. Bijvoorbeeld, deze opties beïnvloeden het berekenen van formules voor grafieken. |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | Retourneert een object dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Zie [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Staat het hashen van aangepaste objecten toe. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analogie van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analogie van C#-operator 'is'. |
| [LoadOptions](./loadoptions/)() | Maakt nieuwe standaard laadopties aan. |
| [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | Maakt nieuwe laadopties aan. |
| void [Lock](../../system/object/lock/)() | Implementeert de locking van de C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waakhondobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Staat het klonen van aangepaste types toe. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | Stelt de opties voor die kunnen worden gebruikt om het gedrag van Binary Large Objects (BLOBs) te beheren, zoals het gebruik van tijdelijke bestanden of maximaal aantal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste verhouding tussen prestaties en geheugengebruik te realiseren voor een specifieke omgeving of vereisten. |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | Stelt het Aziatische lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Schrijf [System::String](../../system/string/). |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | Stelt het reguliere lettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Schrijf [System::String](../../system/string/). |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | Stelt het symboollettertype in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Schrijf [System::String](../../system/string/). |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | Stelt de standaardtaal in voor de presentatie-tekst. Schrijf [System::String](../../system/string/). |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | Bepaalt of [Aspose.Slides](../) alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | Het token om onderbrekingsverzoeken te monitoren. |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | Stelt het formaat van een te laden presentatie in. Schrijf [Slides::LoadFormat](../loadformat/). |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | Deze eigenschap is relevant als het presentatiebestand met een wachtwoord is beveiligd. De waarde true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld presentatiebestand en dat het wachtwoord moet worden genegeerd. De waarde false betekent dat de volledige versleutelde presentatie moet worden geladen met gebruik van het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd. Als documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid. Schrijf **bool**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Stelt het wachtwoord in. Schrijf [System::String](../../system/string/). |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | Stelt de callback-interface in die het laden van externe bronnen beheert. Schrijf [IResourceLoadingCallback](../iresourceloadingcallback/). |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | Haalt opties op voor spreadsheets. Bijvoorbeeld, deze opties beïnvloeden het berekenen van formules voor grafieken. |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Stelt een object in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Schrijf [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in op een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie van C# [Object.ToString()](../../system/object/tostring/)-methode. Staat het converteren van aangepaste objecten naar een string toe. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-waakhondobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [ILoadOptions](../iloadoptions/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)