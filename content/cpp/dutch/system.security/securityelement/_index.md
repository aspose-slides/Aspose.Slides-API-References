---
title: SecurityElement
second_title: Aspose.Slides voor C++ API-referentie
description: "XML-objectmodel voor het coderen van beveiligingsobjecten. Niet geïmplementeerd. Objecten van deze klasse mogen alleen worden toegewezen met behulp van de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om het als argument aan functies door te geven."
type: docs
weight: 40
url: /nl/system.security/securityelement/
---
## SecurityElement klasse

XML-objectmodel voor het coderen van beveiligingsobjecten. Niet geïmplementeerd. Objecten van deze klasse mogen alleen worden toegewezen met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtimefouten en/of assertiefouten veroorzaakt. Wikkel altijd deze klasse in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om het als argument aan functies door te geven.

```cpp
class SecurityElement : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Voegt een attribuut toe aan de tag. |
| void [AddChild](./addchild/)([SecurityElement](./)) | Voegt een kindtag toe. |
| [String](../../system/string/) [Attribute](./attribute/)(const [String](../../system/string/)\&) | Haalt attribuutwaarde op. |
| [SecurityElement](./) [Copy](./copy/)() | Kloont tag. |
| **bool** [Equal](./equal/)([SecurityElement](./)) | Controleert op gelijkheid van parameters. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallenvergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | Escapet tekens in XML-string. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [SecurityElement](./) [FromString](./fromstring/)(const [String](../../system/string/)\&) | Maakt element aan vanuit XML-code. |
| [System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\> [get_Attributes](./get_attributes/)() | Haalt tag-attributen op. |
| [System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\> [get_Children](./get_children/)() | Haalt kindobjecten van tag op. |
| [String](../../system/string/) [get_Tag](./get_tag/)() | Haalt tagnaam op. |
| [String](../../system/string/) [get_Text](./get_text/)() | Haalt interne tekst van tag op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt werkelijke type van object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| static **bool** [IsValidAttributeName](./isvalidattributename/)(const [String](../../system/string/)\&) | Controleert of attribuutnaam geldig is. |
| static **bool** [IsValidAttributeValue](./isvalidattributevalue/)(const [String](../../system/string/)\&) | Controleert of attribuutwaarde geldig is. |
| static **bool** [IsValidTag](./isvalidtag/)(const [String](../../system/string/)\&) | Controleert of tag geldig is. |
| static **bool** [IsValidText](./isvalidtext/)(const [String](../../system/string/)\&) | Controleert of tekst geldig is. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentry-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| [SecurityElement](./) [SearchForChildByTag](./searchforchildbytag/)(const [String](../../system/string/)\&) | Haalt kindtag op op naam. |
| [String](../../system/string/) [SearchForTextOfTag](./searchfortextoftag/)(const [String](../../system/string/)\&) | Haalt interne tekst van kindtag op op tag-naam. |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&) | Constructor. |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Constructor. |
| void [set_Attributes](./set_attributes/)([System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\>) | Stelt tag-attributen in. |
| void [set_Children](./set_children/)([System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\>) | Stelt kindobjecten van tag in. |
| void [set_Tag](./set_tag/)(const [String](../../system/string/)\&) | Stelt tagnaam in. |
| void [set_Text](./set_text/)(const [String](../../system/string/)\&) | Stelt interne tekst van tag in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n'th sjabloonargument in als een zwakke pointer (i.p.v. gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Converteert tag naar string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement unlocking. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) sentry-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Security](../)
* Bibliotheek [Aspose.Slides](../../)