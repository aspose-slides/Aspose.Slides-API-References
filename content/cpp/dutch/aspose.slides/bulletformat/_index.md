---
title: BulletFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de bulletopmaak-eigenschappen van een alinea voor.
type: docs
weight: 248
url: /nl/aspose.slides/bulletformat/
---
## BulletFormat klasse

Stelt de bulletopmaak-eigenschappen van een alinea voor.

```cpp
class BulletFormat : public Aspose::Slides::PVIObject,
                     public Aspose::Slides::IBulletFormat
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() override | Stelt standaard niet-nul verschuivingen in voor de effectieve alinea-Indent en MarginLeft wanneer bullets zijn ingeschakeld (zoals PowerPoint doet als alinea-bullets/nummering wordt ingeschakeld). Als bullets zijn uitgeschakeld wordt alleen de alinea-Indent en MarginLeft gereset (zoals PowerPoint doet als alinea-bullets/nummering wordt uitgeschakeld). Indent-verschuivingen worden toegepast met betrekking tot de huidige bullet-context – IBulletFormat::get(set)_Type, .NumberedBulletStyle en FontHeight van het eerste gedeelte. Niet-nul indent-verschuivingen worden toegepast op de effectieve Indent en MarginLeft van de huidige alinea (zodat resultaatswaarden lokale waarden zijn). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergelijkt met het opgegeven object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert drijvende-komma-vergelijking in C#-stijl waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert drijvende-komma-vergelijking in C#-stijl waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| char16_t [get_Char](./get_char/)() override | Retourneert het bullet-teken van een alinea zonder overerving. Lees **wchar_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() override | Retourneert het kleurobject van een bullet van een alinea zonder overerving. Alleen-lezen [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() override | Retourneert het bullet-lettertype van een alinea zonder overerving. Lees [IFontData](../ifontdata/). |
| **float** [get_Height](./get_height/)() override | Retourneert de bullet-hoogte van een alinea zonder overerving. De waarde std::numeric_limits<float>::quiet_NaN() bepaalt dat de bullet de hoogte erft van het eerste gedeelte in de alinea. Lees **float**. |
| [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() override | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. **[NullableBool::True](../nullablebool/)** als de bullet een eigen kleur heeft en **[NullableBool::False](../nullablebool/)** als de bullet de kleur erft van het eerste gedeelte in de alinea. Lees [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() override | Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste gedeelte in de alinea. **[NullableBool::True](../nullablebool/)** als de bullet een eigen lettertype heeft en **[NullableBool::False](../nullablebool/)** als de bullet het lettertype erft van het eerste gedeelte in de alinea. Lees [NullableBool](../nullablebool/). |
| **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() override | Retourneert het eerste getal dat wordt gebruikt voor een groep genummerde bullets zonder overerving. Lees **int16_t**. |
| [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() override | Retourneert de stijl van een genummerde bullet zonder overerving. Lees [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retourneert het Parent_Immediate-object. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retourneert de bovenliggende [IPresentationComponent](../ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Retourneert de afbeelding die wordt gebruikt als bullet in een alinea zonder overerving. Alleen-lezen [ISlidesPicture](../islidespicture/). |
| [BulletType](../bullettype/) [get_Type](./get_type/)() override | Retourneert het bullet-type van een alinea zonder overerving. Lees [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller-datastructuur op die aan het object is gekoppeld. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() override | Haalt de effectieve bullet-opmaakgegevens op met de toegepaste overerving. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retourneert de hash-code. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Direct aanroepen of [LockContext](../../system/lockcontext/)-sentry-object gebruiken. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets echt, initialiseert alleen nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type-object op referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Char](./set_char/)(char16_t) override | Stelt het bullet-teken van een alinea zonder overerving in. Schrijf **wchar_t**. |
| void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Stelt het bullet-lettertype van een alinea zonder overerving in. Schrijf [IFontData](../ifontdata/). |
| void [set_Height](./set_height/)(**float**) override | Stelt de bullet-hoogte van een alinea zonder overerving in. De waarde std::numeric_limits<float>::quiet_NaN() bepaalt dat de bullet de hoogte erft van het eerste gedeelte in de alinea. Schrijf **float**. |
| void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) override | Bepaalt of de bullet een eigen kleur heeft of deze erft van het eerste gedeelte in de alinea. **[NullableBool::True](../nullablebool/)** als de bullet een eigen kleur heeft en **[NullableBool::False](../nullablebool/)** als de bullet de kleur erft van het eerste gedeelte in de alinea. Schrijf [NullableBool](../nullablebool/). |
| void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) override | Bepaalt of de bullet een eigen lettertype heeft of dit erft van het eerste gedeelte in de alinea. **[NullableBool::True](../nullablebool/)** als de bullet een eigen lettertype heeft en **[NullableBool::False](../nullablebool/)** als de bullet het lettertype erft van het eerste gedeelte in de alinea. Schrijf [NullableBool](../nullablebool/). |
| void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) override | Stelt het eerste getal in dat wordt gebruikt voor een groep genummerde bullets zonder overerving. Schrijf **int16_t**. |
| void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) override | Stelt de stijl in van een genummerde bullet zonder overerving. Schrijf [Slides::NumberedBulletStyle](../numberedbulletstyle/). |
| void [set_Type](./set_type/)([BulletType](../bullettype/)) override | Stelt het bullet-type in van een alinea zonder overerving. Schrijf [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloon-argument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Direct aanroepen of [LockContext](../../system/lockcontext/)-sentry-object gebruiken. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [PVIObject](../pviobject/)
* Klasse [IBulletFormat](../ibulletformat/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)