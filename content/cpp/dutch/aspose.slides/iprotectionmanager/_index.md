---
title: IProtectionManager
second_title: Aspose.Slides voor C++ API-referentie
description: Beheer van wachtwoordbeveiliging van presentaties.
type: docs
weight: 3459
url: /nl/aspose.slides/iprotectionmanager/
---
## IProtectionManager klasse


[Presentation](../presentation/) wachtwoordbeschermingsbeheer.

```cpp
class IProtectionManager : public virtual System::Object
```

## Methoden

| Method | Beschrijving |
| --- | --- |
| virtual **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) | Bepaalt of een presentatie met wachtwoord is beschermd tegen wijzigen. |
| virtual void [Encrypt](./encrypt/)([System::String](../../system/string/)) | Versleutelt [Presentation](../presentation/) met het opgegeven wachtwoord. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagelijkheid waarbij twee NaN’s als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagelijkheid waarbij twee NaN’s als gelijk worden beschouwd, ook al is NaN volgens IEC 60559:1989 niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| virtual **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() | Deze eigenschap is relevant als de presentatie met wachtwoord is beveiligd. Als **true** dan zijn documenteigenschappen versleuteld in het presentatie-bestand. Als **false** dan zijn documenteigenschappen openbaar terwijl de presentatie versleuteld is. Lezen **bool**. |
| virtual [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() | Levert het encryptiewachtwoord. Alleen-lezen [System::String](../../system/string/). |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() | Geeft aan of deze instantie versleuteld is. Alleen-lezen **bool**. |
| virtual **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() | Deze eigenschap is relevant als het presentatie-bestand met wachtwoord is beveiligd en de documenteigenschappen van dit bestand openbaar zijn. **true** betekent dat alleen documenteigenschappen worden geladen uit een versleuteld presentatie-bestand zonder gebruik van wachtwoord. **false** betekent dat de gehele versleutelde presentatie wordt geladen met het juiste wachtwoord, niet alleen de documenteigenschappen. Als de presentatie niet versleuteld is, is de eigenschap altijd **false**. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn, is de eigenschap altijd **false**. Als **PresentationEx.EncryptDocumentProperties** **true** is, is **IsOnlyDocumentPropertiesLoaded** altijd **false**. Alleen-lezen **bool**. |
| virtual **bool** [get_IsWriteProtected](./get_iswriteprotected/)() | Geeft aan of deze presentatie schrijf-beveiligd is. Alleen-lezen **bool**. |
| virtual **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() | Geeft een alleen-lezen-aanbeveling. Lezen **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Equivalent van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Schakelt hash-functionaliteit voor aangepaste objecten in. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het actuele type van het object op. Equivalent van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door **targetType**. Equivalent van de C#-'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# **lock()**-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Equivalent van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets, initialiseert slechts een nieuw object en maakt kopiëren van afgeleide klassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert slechts een nieuw object en maakt kopiëren van afgeleide klassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met **nullptr** op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en **nullptr**. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [RemoveEncryption](./removeencryption/)() | Verwijdert de encryptie. |
| virtual void [RemoveWriteProtection](./removewriteprotection/)() | Verwijdert schrijfbeveiliging voor deze presentatie. |
| virtual void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) | Deze eigenschap is relevant als de presentatie met wachtwoord is beveiligd. Als **true** dan zijn documenteigenschappen versleuteld in het presentatie-bestand. Als **false** dan zijn documenteigenschappen openbaar terwijl de presentatie versleuteld is. Schrijven **bool**. |
| virtual void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) | Stelt de alleen-lezen-aanbeveling in. Schrijven **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| virtual void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) | Stelt schrijfbeveiliging voor deze presentatie in met het opgegeven wachtwoord. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of **ThisProtector**. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of **ThisProtector**. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Equivalent van de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# **typeof([System.Object](../../system/object/))**-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert de C# **lock()**-statement voor ontgrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of **ThisProtector**. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of **ThisProtector**. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)