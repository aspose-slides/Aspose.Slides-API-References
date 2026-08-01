---
title: X509Certificate2
second_title: Aspose.Slides voor C++ API-referentie
description: "Vertegenwoordigt een X509-certificaat. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime fouten en/of assertiefouten veroorzaakt. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 40
url: /nl/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 klasse

Vertegenwoordigt een X509-certificaat. Objecten van deze klasse mogen alleen worden gealloceerd met behulp van de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten tot gevolg heeft. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik die pointer om deze aan functies als argument door te geven.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromCertFile](../x509certificate/createfromcertfile/)(const [String](../../system/string/)\&) | Maakt een certificaat aan van het opgegeven PKCS7-bestand. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromSignedFile](../x509certificate/createfromsignedfile/)(const [String](../../system/string/)\&) | Maakt een certificaat aan van het opgegeven ondertekende bestand. |
| void [Dispose](../x509certificate/dispose/)() override | Doet niets. |
| **bool** [Equals](../x509certificate/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Vergelijkt twee certificaten. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Bootst C#-achtige zwevendekomma-vergelijking na waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Bootst C#-achtige zwevendekomma-vergelijking na waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/)) const | Exporteert het huidige object naar een byte-array met behulp van het opgegeven formaat. NIET GEREALISEERD. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Exporteert het huidige object naar een byte-array met behulp van het opgegeven formaat. NIET GEREALISEERD. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Exporteert het huidige object naar een byte-array met behulp van het opgegeven formaat. NIET GEREALISEERD. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_Archived](./get_archived/)() const | Geeft een waarde die aangeeft dat het certificaat gearchiveerd is. |
| [X509ExtensionCollectionPtr](../x509extensioncollectionptr/) [get_Extensions](./get_extensions/)() const | Retourneert de verzameling extensie-objecten die aan het certificaat gekoppeld zijn. |
| [String](../../system/string/) [get_FriendlyName](./get_friendlyname/)() const | Retourneert de vriendelijke naam van het certificaat. |
| IntPtr [get_Handle](../x509certificate/get_handle/)() const | Geeft een handle naar de Microsoft Cryptographic API-certificaat-context. |
| **bool** [get_HasPrivateKey](./get_hasprivatekey/)() const | Controleert of het certificaat een privésleutel heeft. |
| [String](../../system/string/) [get_Issuer](../x509certificate/get_issuer/)() const | Retourneert de naam van de certificaatautoriteit die het X.509v3-certificaat heeft uitgegeven. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_IssuerName](./get_issuername/)() const | Retourneert de naam van de partij die een certificaat heeft uitgegeven. |
| [DateTime](../../system/datetime/) [get_NotAfter](./get_notafter/)() const | Retourneert de lokale datum en tijd waarna een certificaat niet meer geldig is. |
| [DateTime](../../system/datetime/) [get_NotBefore](./get_notbefore/)() const | Retourneert de lokale datum en tijd waarop een certificaat geldig wordt. |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_PrivateKey](./get_privatekey/)() const | Retourneert de privésleutel die aan het certificaat is gekoppeld. |
| [SharedPtr](../../system/sharedptr/)\<[PublicKey](../publickey/)\> [get_PublicKey](./get_publickey/)() const | Retourneert een certificaat [PublicKey](../publickey/)-object. |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](./get_rawdata/)() const | Retourneert de ruwe gegevens van het certificaat. |
| [String](../../system/string/) [get_SerialNumber](./get_serialnumber/)() const | Retourneert het serienummer van een certificaat. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Retourneert het algoritme dat gebruikt wordt om de handtekening van een certificaat te maken. |
| [String](../../system/string/) [get_Subject](../x509certificate/get_subject/)() const | Retourneert de subject distinguished name uit het certificaat. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_SubjectName](./get_subjectname/)() const | Retourneert de subject-naam uit een certificaat. |
| [String](../../system/string/) [get_Thumbprint](./get_thumbprint/)() const | Retourneert de vingerafdruk van het certificaat. |
| **int32_t** [get_Version](./get_version/)() const | Retourneert de versie van het certificaatformaat. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Retourneert het type certificaat dat zich in de opgegeven byte-array bevindt. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [String](../../system/string/)\&) | Retourneert het type certificaat dat zich in het opgegeven bestand bevindt. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)() const | Retourneert de hash van het huidige object als een byte-array. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Retourneert de hash van het huidige object als een byte-array. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)() const | Retourneert de [SHA1](../../system.security.cryptography/sha1/)-hash van het huidige object als een hexadecimale string. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Retourneert de [SHA1](../../system.security.cryptography/sha1/)-hash van het huidige object als een hexadecimale string. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Retourneert de referentie-teller-datastructuur die aan het object is gekoppeld. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPrivateKey](./getdsaprivatekey/)() const | Retourneert de [RSA](../../system.security.cryptography/rsa/) privésleutel; |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPublicKey](./getdsapublickey/)() const | Retourneert de [RSA](../../system.security.cryptography/rsa/) publieke sleutel. |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Retourneert de [RSA](../../system.security.cryptography/rsa/) privésleutel; |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPublicKey](./getecdsapublickey/)() const | Retourneert de [RSA](../../system.security.cryptography/rsa/) publieke sleutel. |
| virtual [String](../../system/string/) [GetEffectiveDateString](../x509certificate/geteffectivedatestring/)() const | Retourneert de ingangsdatum van het huidige certificaat. |
| virtual [String](../../system/string/) [GetExpirationDateString](../x509certificate/getexpirationdatestring/)() const | Retourneert de vervaldatum van het huidige certificaat. |
| virtual [String](../../system/string/) [GetFormat](../x509certificate/getformat/)() const | Retourneert de naam van het certificaatformaat. |
| **int32_t** [GetHashCode](../x509certificate/gethashcode/)() const override | Retourneert de hash-code van het certificaat. |
| virtual [String](../../system/string/) [GetIssuerName](../x509certificate/getissuername/)() const | Retourneert de naam van de certificaatautoriteit die het huidige certificaat heeft uitgegeven. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](../x509certificate/getkeyalgorithm/)() const | Retourneert sleutel-informatie voor het huidige certificaat als een string. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](../x509certificate/getkeyalgorithmparameters/)() const | Retourneert sleutel-informatie voor het huidige certificaat als een byte-array. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](../x509certificate/getkeyalgorithmparametersstring/)() const | Retourneert sleutel-informatie voor het huidige certificaat als een hexadecimale string. |
| virtual [String](../../system/string/) [GetName](../x509certificate/getname/)() const | Retourneert de naam van de principal aan wie het huidige certificaat is uitgegeven. |
| [String](../../system/string/) [GetNameInfo](./getnameinfo/)([X509NameType](../x509nametype/), **bool**) const | Retourneert subject- of issuer-naam uit het certificaat. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](../x509certificate/getpublickey/)() const | Retourneert de publieke sleutel van het certificaat als een byte-array. |
| virtual [String](../../system/string/) [GetPublicKeyString](../x509certificate/getpublickeystring/)() const | Retourneert de publieke sleutel van het certificaat als een hexadecimale string. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](../x509certificate/getrawcertdata/)() const | Retourneert ruwe gegevens van het certificaat als een byte-array. |
| virtual [String](../../system/string/) [GetRawCertDataString](../x509certificate/getrawcertdatastring/)() const | Retourneert ruwe gegevens van het certificaat als een hexadecimale string. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPrivateKey](./getrsaprivatekey/)() const | Retourneert de [RSA](../../system.security.cryptography/rsa/) privésleutel; |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPublicKey](./getrsapublickey/)() const | Retourneert de [RSA](../../system.security.cryptography/rsa/) publieke sleutel. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](../x509certificate/getserialnumber/)() const | Retourneert het serienummer van het certificaat als een byte-array. |
| virtual [String](../../system/string/) [GetSerialNumberString](../x509certificate/getserialnumberstring/)() const | Retourneert het serienummer van het certificaat als een hexadecimale string. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Retourneert het werkelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importeert informatie uit het opgegeven certificaatbestand. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importeert informatie uit het opgegeven certificaatbestand. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importeert informatie uit de opgegeven certificaatgegevens. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importeert informatie uit de opgegeven certificaatgegevens. |
| void [Import](./import/)(const [String](../../system/string/)\&) override | Importeert informatie uit het opgegeven certificaatbestand. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | Importeert informatie uit de opgegeven certificaatgegevens. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock()-statement voor locking. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemersobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert in feite niets, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [X509Certificate](../x509certificate/)\& [operator=](../x509certificate/operator_equal/)(const [X509Certificate](../x509certificate/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment-operator. Kopieert in feite niets, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van een string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [Reset](./reset/)() override | Reset de certificaatstatus. |
| void [set_Archived](./set_archived/)(**bool**) const | Stelt een waarde in die aangeeft dat het certificaat gearchiveerd is. |
| void [set_FriendlyName](./set_friendlyname/)(const [String](../../system/string/)\&) | Stelt de vriendelijke naam van het certificaat in. |
| void [set_PrivateKey](./set_privatekey/)(const [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) | Stelt de privésleutel die aan het certificaat gekoppeld is in of wist deze. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloon-argument in op een zwakke pointer (in plaats van gedeeld). Stelt toe pointers in containers te wisselen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Retourneert de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)(**bool**) const override | Retourneert de certificaatinformatie in tekstformaat. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Retourneert de certificaatinformatie in tekstformaat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert de C# lock()-statement voor unlocking. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarnemersobject. |
| **bool** [Verify](./verify/)() const | Verifieert de certificaatketen. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [X509Certificate](../x509certificate/)\&) |  |
|  [X509Certificate](../x509certificate/x509certificate/)() | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)() | Constructs empty [X509Certificate2](./). |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Constructor. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Zie ook

* Klasse [X509Certificate](../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../)
* Bibliotheek [Aspose.Slides](../../)