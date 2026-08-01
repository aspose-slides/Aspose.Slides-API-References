---
title: RC2Managed
second_title: Aspose.Slides voor C++ API-referentie
description: "Beheerde RC2-algoritme. Alleen ECB-, CFB- en CBC-ciphermodi worden ondersteund. Objecten van deze klasse mogen alleen worden toegewezen met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wrap deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 378
url: /nl/system.security.cryptography/rc2managed/
---
## RC2Managed klasse

Managed [RC2](../rc2/) algoritme. Alleen ECB, CFB en CBC-cipher modi worden ondersteund. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class RC2Managed : public System::Security::Cryptography::RC2
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | Maakt een instantie van het algoritme aan. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Maakt een decryptor-object aan met expliciete parameters. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | Maakt een decryptor-object aan met parameters gedefinieerd door het algoritme-object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Maakt een decryptor-object aan met parameters gedefinieerd door het algoritme-object. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Maakt een encryptor-object aan met expliciete parameters. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | Maakt een encryptor-object aan met parameters gedefinieerd door het algoritme-object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Maakt een encryptor-object aan met parameters gedefinieerd door het algoritme-object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 is NaN niet gelijk aan een enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, zelfs volgens IEC 60559:1989 is NaN niet gelijk aan een enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| void [GenerateIV](./generateiv/)() override | Maakt een willekeurige initiële waarde aan en slaat deze op in de interne gegevens van het algoritme. |
| void [GenerateKey](./generatekey/)() override | Maakt een willekeurige sleutel aan en slaat deze op in de interne gegevens van het algoritme. |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | Haal de blokgrootte van de cryptografische bewerking op. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | Haal de feedback-grootte van de cryptografische bewerking op. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | Haal de initiële waarde van de cryptografische bewerking op. Maakt een nieuwe aan indien nog niet aangemaakt. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | Haal de sleutel van de cryptografische bewerking op. Maakt een nieuwe aan indien nog niet aangemaakt. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | Haal de sleutelgrootte van de cryptografische bewerking op. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | Haal de modus van de cryptografische bewerking op. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | Haal de opvulling van de cryptografische bewerking op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haal de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge methode van C# [Object.GetHashCode()](../../system/object/gethashcode/). Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haal het werkelijke type van het object op. Analoge aanroep van C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type beschreven door targetType is. Analoge aan C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock() statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewaakobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge methode van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, initialiseert simpelweg een nieuw object en maakt kopiëren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert simpelweg een nieuw object en maakt kopiëren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr via referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | Stelt de blokgrootte van de cryptografische bewerking in. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | Stelt de feedback-grootte van de cryptografische bewerking in. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Stelt de initiële waarde van de cryptografische bewerking in. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Stelt de sleutel van de cryptografische bewerking in. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | Stelt de sleutelgrootte van de cryptografische bewerking in. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | Stelt de modus van de cryptografische bewerking in. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | Stelt de opvulling van de cryptografische bewerking in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haal de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge methode van C# [Object.ToString()](../../system/object/tostring/). Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock() statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewaakobject. |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | Controleert of de sleutelgrootte geldig is. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [RC2](../rc2/)
* Namespace [System::Security::Cryptography](../)
* Bibliotheek [Aspose.Slides](../../)