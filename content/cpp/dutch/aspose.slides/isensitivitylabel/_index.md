---
title: ISensitivityLabel
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt het gevoeligheidslabel van Microsoft Purview Information Protection voor.
type: docs
weight: 3615
url: /nl/aspose.slides/isensitivitylabel/
---
## ISensitivityLabel klasse

Stelt het gevoeligheidslabel van Microsoft Purview Information Protection voor.

```cpp
class ISensitivityLabel : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl drijvende-kommagelijken waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl drijvende-kommagelijken waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/) [get_AssignmentMethodType](./get_assignmentmethodtype/)() | Geeft de toewijzingsmethode voor het gevoeligheidslabel terug. Lees [SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SensitivityLabelContentType](../sensitivitylabelcontenttype/)\>\> [get_ContentMarkTypes](./get_contentmarktypes/)() | Geeft de lijst met typen van inhoudsmarkering die op een bestand moet worden toegepast terug. |
| virtual [System::String](../../system/string/) [get_Id](./get_id/)() | Geeft de id van het gevoeligheidslabel terug. Lees [System::String](../../system/string/). |
| virtual **bool** [get_IsEnabled](./get_isenabled/)() | Geeft aan of het gevoeligheidslabel is ingeschakeld. |
| virtual **bool** [get_IsRemoved](./get_isremoved/)() | Geeft aan of het gevoeligheidslabel is verwijderd. |
| virtual [System::Guid](../../system/guid/) [get_SiteId](./get_siteid/)() | Geeft de Azure Active Directory (Azure AD) site-identificatie terug die overeenkomt met het gevoeligheidslabelbeleid dat het gevoeligheidslabel beschrijft. Lees [System::Guid](../../system/guid/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of object een instantie van het type dat wordt beschreven door targetType vertegenwoordigt. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopiekonstruktie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopiekonstruktie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AssignmentMethodType](./set_assignmentmethodtype/)([SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/)) | Stelt de toewijzingsmethode voor het gevoeligheidslabel in. Schrijf [SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/). |
| virtual void [set_Id](./set_id/)([System::String](../../system/string/)) | Stelt de id van het gevoeligheidslabel in. Schrijf [System::String](../../system/string/). |
| virtual void [set_IsEnabled](./set_isenabled/)(**bool**) | Geeft aan of het gevoeligheidslabel is ingeschakeld. |
| virtual void [set_IsRemoved](./set_isremoved/)(**bool**) | Geeft aan of het gevoeligheidslabel is verwijderd. |
| virtual void [set_SiteId](./set_siteid/)([System::Guid](../../system/guid/)) | Stelt de Azure Active Directory (Azure AD) site-identificatie in die overeenkomt met het gevoeligheidslabelbeleid dat het gevoeligheidslabel beschrijft. Schrijf [System::Guid](../../system/guid/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-template-argument in op een zwakke pointer (in plaats van gedeeld). Stelt u in staat om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides](../)
* Library [Aspose.Slides](../../)