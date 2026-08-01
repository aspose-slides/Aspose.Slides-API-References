---
title: ProtectionManager
second_title: Aspose.Slides voor C++ API-referentie
description: Beheer van wachtwoordbeveiliging van presentaties.
type: docs
weight: 4915
url: /nl/aspose.slides/protectionmanager/
---
## ProtectionManager klasse


[Presentation](../presentation/) wachtwoordbeveiligingsbeheer.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | Bepaalt of een presentatie met een wachtwoord beveiligd is om te wijzigen. |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | Versleutelt [Presentation](../presentation/) met het opgegeven wachtwoord. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | Deze eigenschap heeft zin als de presentatie met een wachtwoord beveiligd is. Als waar, dan zijn de documenteigenschappen versleuteld in het presentatiebestand. Als onwaar, dan zijn de documenteigenschappen openbaar terwijl de presentatie versleuteld is. Lezen **bool**. |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | Haalt het wachtwoord op dat wordt gebruikt voor presentatieversleuteling. Alleen-lezen [System::String](../../system/string/). |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | Haalt een waarde op die aangeeft of dit exemplaar versleuteld is. Alleen-lezen **bool**. |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | Deze eigenschap heeft zin als het presentatiebestand met een wachtwoord beveiligd is en de documenteigenschappen van dit bestand openbaar zijn. Waarde true betekent dat alleen documenteigenschappen worden geladen uit een versleuteld presentatiebestand zonder gebruik van een wachtwoord. Waarde false betekent dat de volledige versleutelde presentatie wordt geladen met gebruik van het juiste wachtwoord, niet alleen documenteigenschappen worden geladen. Als de presentatie niet versleuteld is, dan is de eigenschapswaarde altijd false. Als documenteigenschappen van een versleuteld bestand niet openbaar zijn, dan is de eigenschapswaarde altijd false. Als Presentation.EncryptDocumentProperties true is, dan is de eigenschap IsOnlyDocumentPropertiesLoaded altijd false. Alleen-lezen **bool**. |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | Haalt een waarde op die aangeeft of deze presentatie schrijfbeveiligd is. Alleen-lezen **bool**. |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | Haalt alleen-lezen aanbeveling op. Lezen **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analog van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waarschuwingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [RemoveEncryption](./removeencryption/)() override | Verwijdert de versleuteling. |
| void [RemoveWriteProtection](./removewriteprotection/)() override | Verwijdert de schrijfbeveiliging voor deze presentatie. |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | Deze eigenschap heeft zin als de presentatie met een wachtwoord beveiligd is. Als waar, dan zijn de documenteigenschappen versleuteld in het presentatiebestand. Als onwaar, dan zijn de documenteigenschappen openbaar terwijl de presentatie versleuteld is. Schrijf **bool**. |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | Stelt alleen-lezen aanbeveling in. Schrijf **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | Stel schrijfbeveiliging voor deze presentatie in met het opgegeven wachtwoord. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) waarschuwingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Zou niet direct aangeroepen moeten worden; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijeft alle interne datastructuren. |

## Zie ook

* Klasse [IProtectionManager](../iprotectionmanager/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)