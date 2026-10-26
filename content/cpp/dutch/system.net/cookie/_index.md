---
title: Cookie
second_title: Aspose.Slides voor C++ API Referentie
description: "Vertegenwoordigt een HTTP-cookie. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Pak deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om het als argument aan functies door te geven."
type: docs
weight: 1
url: /nl/system.net/cookie/
---
## Cookie klasse

Representeert een HTTP-cookie. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een exemplaar van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Pak deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om het als argument aan functies door te geven.

```cpp
class Cookie : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Maakt een kopie van de huidige instantie. |
|  [Cookie](./cookie/)() | Construeert een nieuw exemplaar. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Construeert een nieuw exemplaar. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Construeert een nieuw exemplaar. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Construeert een nieuw exemplaar. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagelijk vergelijken waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagelijk vergelijken waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Haalt de waarde van het 'Comment'-attribuut op. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Haalt de waarde van het 'CommentURL'-attribuut op. |
| **bool** [get_Discard](./get_discard/)() const | Haalt de waarde van het 'Discard'-attribuut op. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Haalt de waarde van het 'Domain'-attribuut op. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Haalt een waarde op die aangeeft of het domein impliciet is. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Retourneert de domeinsleutel. |
| **bool** [get_Expired](./get_expired/)() | Haalt een waarde op die aangeeft of de cookie verlopen is. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Haalt de waarde van het 'Expires'-attribuut op. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Haalt de waarde van het 'HttpOnly'-attribuut op. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Haalt de naam van de cookie op. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Haalt de waarde van het 'Path'-attribuut op. |
| **bool** [get_Plain](./get_plain/)() const | Retourneert een waarde die aangeeft of de cookie-specificatie 'Plain' is. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Haalt de waarde van het 'Port'-attribuut op. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Retourneert de verzameling van de waarden van het 'Port'-attribuut. |
| **bool** [get_Secure](./get_secure/)() const | Haalt de waarde van het 'Secure'-attribuut op. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Retourneert het moment waarop de cookie werd aangemaakt. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Haalt de waarde van de cookie op. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Haalt de specificatie van de cookie op. |
| **int32_t** [get_Version](./get_version/)() const | Haalt de waarde van het '[Version](../../system/version/)'-attribuut op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analoge C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Deze methode wordt door andere methoden aangeroepen om een methodenaam in te stellen. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een exemplaar is van het type beschreven door targetType. Analoge C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Stelt de waarde van het 'Comment'-attribuut in. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Stelt de waarde van het 'CommentURL'-attribuut in. |
| void [set_Discard](./set_discard/)(**bool**) | Stelt de waarde van het 'Discard'-attribuut in. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Stelt de waarde van het 'Domain'-attribuut in. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Stelt een waarde in die aangeeft of het domein impliciet is. |
| void [set_Expired](./set_expired/)(**bool**) | Stelt een waarde in die aangeeft of de cookie verlopen is. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Stelt de waarde van het 'Expires'-attribuut in. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Stelt de waarde van het 'HttpOnly'-attribuut in. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Stelt de naam van de cookie in. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Stelt de waarde van het 'Path'-attribuut in. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Stelt de waarde van het 'Port'-attribuut in. |
| void [set_Secure](./set_secure/)(**bool**) | Stelt de waarde van het 'Secure'-attribuut in. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Stelt de waarde van de cookie in. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Stelt de specificatie van de cookie in. |
| void [set_Version](./set_version/)(**int32_t**) | Stelt de waarde van het '[Version](../../system/version/)'-attribuut in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Vermindert en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Serialiseert de huidige instantie naar de tekenreeksrepresentatie. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Analoge C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar een string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het lock()-statement van C# voor ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Verifieert en stelt de standaardwaarden van het attribuut in. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Vermindert de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne gegevensstructuren. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | De naam van het 'Comment'-attribuut. |
| static [CommentUrlAttributeName](./commenturlattributename/) | De naam van het 'CommentURL'-attribuut. |
| static [DiscardAttributeName](./discardattributename/) | De naam van het 'Discard'-attribuut. |
| static [DomainAttributeName](./domainattributename/) | De naam van het 'Domain'-attribuut. |
| static [EqualsLiteral](./equalsliteral/) | Het scheidingsteken dat wordt gebruikt om de naam en waarde van een attribuut te scheiden. |
| static [ExpiresAttributeName](./expiresattributename/) | De naam van het 'Expires'-attribuut. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | De naam van het 'HttpOnly'-attribuut. |
| static [MaxAgeAttributeName](./maxageattributename/) | De naam van het 'Max-Age'-attribuut. |
| static [MaxSupportedVersion](./maxsupportedversion/) | De maximaal ondersteunde versie. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | De tekenreeksrepresentatie van de maximaal ondersteunde versie. |
| static [PathAttributeName](./pathattributename/) | De naam van het 'Path'-attribuut. |
| static [PortAttributeName](./portattributename/) | De naam van het 'Port'-attribuut. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | De array die scheidingstekens bevat voor de waarden van het 'Port'-attribuut. |
| static [QuotesLiteral](./quotesliteral/) | Het symbool dat wordt gebruikt om de delen van het attribuut te omhullen. |
| static [ReservedToName](./reservedtoname/) | Een waarde die gereserveerd is voor de cookie-naam. |
| static [ReservedToValue](./reservedtovalue/) | Een waarde die gereserveerd is voor de cookie-waarde. |
| static [SecureAttributeName](./secureattributename/) | De naam van het 'Secure'-attribuut. |
| static [SeparatorLiteral](./separatorliteral/) | De attribuutscheidingsteken. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Het voorvoegsel van de namen van speciale attributen. |
| static [VersionAttributeName](./versionattributename/) | De naam van het '[Version](../../system/version/)'-attribuut. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Net](../)
* Bibliotheek [Aspose.Slides](../../)