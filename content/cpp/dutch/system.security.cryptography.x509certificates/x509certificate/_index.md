---
title: X509Certificate
second_title: Aspose.Slides voor C++ API-referentie
description: "X.509 v.3 certificaat. Versleutelde certificaten worden niet ondersteund. Alleen de vlag X509KeyStorageFlags::DefaultKeySet wordt ondersteund. Objecten van deze klasse mogen alleen worden gealloceerd met de functie System::MakeObject(). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit tot runtime-fouten en/of assert-fouten leidt. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik die pointer om deze als argument aan functies door te geven."
type: docs
weight: 27
url: /nl/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate klasse


X.509 v.3 certificaat. Versleutelde certificaten worden niet ondersteund. Alleen [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/)-vlag wordt ondersteund. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assert-fouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies te doorgeven.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## Methods

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | Maakt een certificaat aan van het opgegeven PKCS7-bestand. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | Maakt een certificaat aan van het opgegeven ondertekende bestand. |
| void [Dispose](./dispose/)() override | Doet niets. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt twee certificaten. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-komma vergelijking waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | Exporteert het huidige object naar een byte-array met het opgegeven formaat. NIET GEREALISEERD. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Exporteert het huidige object naar een byte-array met het opgegeven formaat. NIET GEREALISEERD. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Exporteert het huidige object naar een byte-array met het opgegeven formaat. NIET GEREALISEERD. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| IntPtr [get_Handle](./get_handle/)() const | Haalt een handle op voor de Microsoft Cryptographic API certificaatcontext. |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | Haalt de naam op van de certificaatautoriteit die het X.509v3-certificaat heeft uitgegeven. |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | Haalt de subject distinguished name uit het certificaat. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | Haalt de hash op van het huidige object als een byte-array. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Haalt de hash op van het huidige object als een byte-array. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | Haalt de [SHA1](../../system.security.cryptography/sha1/)-hash op van het huidige object als een hexadecimale string. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Haalt de [SHA1](../../system.security.cryptography/sha1/)-hash op van het huidige object als een hexadecimale string. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | Haalt de geldigheidsdatum op van het huidige certificaat. |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | Haalt de vervaldatum op van het huidige certificaat. |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | Haalt de naam op van het certificaatformaat. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Haalt de certificaat-hashcode op. |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | Haalt de naam op van de certificaatautoriteit die het huidige certificaat heeft uitgegeven. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | Haalt de sleutel-informatie op van het huidige certificaat als een string. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | Haalt de sleutel-informatie op van het huidige certificaat als een byte-array. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | Haalt de sleutel-informatie op van het huidige certificaat als een hexadecimale string. |
| virtual [String](../../system/string/) [GetName](./getname/)() const | Haalt de naam op van de principal aan wie het huidige certificaat is uitgegeven. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | Haalt de publieke sleutel op uit het certificaat als een byte-array. |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | Haalt de publieke sleutel op uit het certificaat als een hexadecimale string. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | Haalt de ruwe data op uit het certificaat als een byte-array. |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | Haalt de ruwe data op uit het certificaat als een hexadecimale string. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | Haalt het serienummer op uit het certificaat als een byte-array. |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | Haalt het serienummer op uit het certificaat als een hexadecimale string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importeert informatie uit het opgegeven certificaatbestand. NIET GEREALISEERD. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importeert informatie uit het opgegeven certificaatbestand. NIET GEREALISEERD. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importeert informatie uit de opgegeven certificaatdata. NIET GEREALISEERD. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importeert informatie uit de opgegeven certificaatdata. NIET GEREALISEERD. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | Importeert informatie uit het opgegeven certificaatbestand. NIET GEREALISEERD. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Importeert informatie uit de opgegeven certificaatdata. NIET GEREALISEERD. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentry-object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert gewoon een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [Reset](./reset/)() | Reset de certificaatstatus. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt overschakelen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde op van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | Retourneert de certificaatinformatie in tekstformaat. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Retourneert de certificaatinformatie in tekstformaat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert de C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-sentry-object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | Constructor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Pointer-type. |
## Zie ook

* Klasse [Object](../../system/object/)
* Klasse [IDisposable](../../system/idisposable/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Bibliotheek [Aspose.Slides](../../)