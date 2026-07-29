---
title: X509Certificate2
second_title: Aspose.Slides för C++ API-referens
description: "Representerar X509-certifikat. Objekt av denna klass bör endast allokeras med funktionen System::MakeObject(). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument."
type: docs
weight: 40
url: /sv/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 klass


Representerar X509-certifikat. Objekt av denna klass bör endast allokeras med funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromCertFile](../x509certificate/createfromcertfile/)(const [String](../../system/string/)\&) | Skapar certifikat från den angivna PKCS7-filen. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromSignedFile](../x509certificate/createfromsignedfile/)(const [String](../../system/string/)\&) | Skapar certifikat från den angivna signerade filen. |
| void [Dispose](../x509certificate/dispose/)() override | Gör ingenting. |
| **bool** [Equals](../x509certificate/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Jämför två certifikat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stilens jämförelse av flyttal där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stilens jämförelse av flyttal där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/)) const | Exporterar det aktuella objektet till en byte-array med det angivna formatet. INTE IMPLEMENTERAT. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Exporterar det aktuella objektet till en byte-array med det angivna formatet. INTE IMPLEMENTERAT. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Exporterar det aktuella objektet till en byte-array med det angivna formatet. INTE IMPLEMENTERAT. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **bool** [get_Archived](./get_archived/)() const | Hämtar ett värde som indikerar att certifikatet är arkiverat. |
| [X509ExtensionCollectionPtr](../x509extensioncollectionptr/) [get_Extensions](./get_extensions/)() const | Hämtar samling av tilläggsobjekt som är associerade med certifikatet. |
| [String](../../system/string/) [get_FriendlyName](./get_friendlyname/)() const | Hämtar certifikatets vänliga namn. |
| IntPtr [get_Handle](../x509certificate/get_handle/)() const | Hämtar ett handtag till Microsoft Cryptographic API-certifikatkontext. |
| **bool** [get_HasPrivateKey](./get_hasprivatekey/)() const | Kontrollerar om certifikatet har en privat nyckel. |
| [String](../../system/string/) [get_Issuer](../x509certificate/get_issuer/)() const | Hämtar namnet på certifikatutfärdaren som utfärdade X.509v3-certifikatet. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_IssuerName](./get_issuername/)() const | Hämtar namnet på den part som utfärdade ett certifikat. |
| [DateTime](../../system/datetime/) [get_NotAfter](./get_notafter/)() const | Hämtar lokalt datum och tid efter vilket ett certifikat inte längre är giltigt. |
| [DateTime](../../system/datetime/) [get_NotBefore](./get_notbefore/)() const | Hämtar lokalt datum och tid då ett certifikat blir giltigt. |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_PrivateKey](./get_privatekey/)() const | Hämtar privat nyckel associerad med certifikatet. |
| [SharedPtr](../../system/sharedptr/)\<[PublicKey](../publickey/)\> [get_PublicKey](./get_publickey/)() const | Hämtar ett [PublicKey](../publickey/)-objekt. |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](./get_rawdata/)() const | Hämtar certifikatets rådata. |
| [String](../../system/string/) [get_SerialNumber](./get_serialnumber/)() const | Hämtar serienumret för ett certifikat. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Hämtar algoritmen som används för att skapa signaturen på ett certifikat. |
| [String](../../system/string/) [get_Subject](../x509certificate/get_subject/)() const | Hämtar det distinguerade ämnesnamnet från certifikatet. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_SubjectName](./get_subjectname/)() const | Hämtar ämnesnamnet från ett certifikat. |
| [String](../../system/string/) [get_Thumbprint](./get_thumbprint/)() const | Hämtar certifikatets tumavtryck. |
| **int32_t** [get_Version](./get_version/)() const | Hämtar versionen av certifikatformatet. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Hämtar typen av certifikat som finns i den angivna byte-arrayen. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [String](../../system/string/)\&) | Hämtar typen av certifikat som finns i den angivna filen. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)() const | Hämtar hash för det aktuella objektet som en byte-array. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Hämtar hash för det aktuella objektet som en byte-array. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)() const | Hämtar [SHA1](../../system.security.cryptography/sha1/)-hash för det aktuella objektet som en hexadecimal sträng. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Hämtar [SHA1](../../system.security.cryptography/sha1/)-hash för det aktuella objektet som en hexadecimal sträng. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPrivateKey](./getdsaprivatekey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/)-privata nyckel;. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPublicKey](./getdsapublickey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/)-offentlig nyckel. |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/)-privata nyckel;. |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPublicKey](./getecdsapublickey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/)-offentlig nyckel. |
| virtual [String](../../system/string/) [GetEffectiveDateString](../x509certificate/geteffectivedatestring/)() const | Hämtar giltighetsdatum för det aktuella certifikatet. |
| virtual [String](../../system/string/) [GetExpirationDateString](../x509certificate/getexpirationdatestring/)() const | Hämtar utgångsdatum för det aktuella certifikatet. |
| virtual [String](../../system/string/) [GetFormat](../x509certificate/getformat/)() const | Hämtar namnet på certifikatformatet. |
| **int32_t** [GetHashCode](../x509certificate/gethashcode/)() const override | Hämtar certifikatets hash-kod. |
| virtual [String](../../system/string/) [GetIssuerName](../x509certificate/getissuername/)() const | Hämtar namnet på certifikatutfärdaren som utfärdade det aktuella certifikatet. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](../x509certificate/getkeyalgorithm/)() const | Hämtar nyckelinformation för det aktuella certifikatet som en sträng. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](../x509certificate/getkeyalgorithmparameters/)() const | Hämtar nyckelinformation för det aktuella certifikatet som en byte-array. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](../x509certificate/getkeyalgorithmparametersstring/)() const | Hämtar nyckelinformation för det aktuella certifikatet som en hexadecimal sträng. |
| virtual [String](../../system/string/) [GetName](../x509certificate/getname/)() const | Hämtar namn på den principal som det aktuella certifikatet utfärdades till. |
| [String](../../system/string/) [GetNameInfo](./getnameinfo/)([X509NameType](../x509nametype/), **bool**) const | Hämtar ämnes- eller utfärdarens namn från certifikatet. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](../x509certificate/getpublickey/)() const | Hämtar den offentliga nyckeln från certifikatet som en byte-array. |
| virtual [String](../../system/string/) [GetPublicKeyString](../x509certificate/getpublickeystring/)() const | Hämtar den offentliga nyckeln från certifikatet som en hexadecimal sträng. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](../x509certificate/getrawcertdata/)() const | Hämtar rådata från certifikatet som en byte-array. |
| virtual [String](../../system/string/) [GetRawCertDataString](../x509certificate/getrawcertdatastring/)() const | Hämtar rådata från certifikatet som en hexadecimal sträng. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPrivateKey](./getrsaprivatekey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/)-privata nyckel;. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPublicKey](./getrsapublickey/)() const | Hämtar [RSA](../../system.security.cryptography/rsa/)-offentlig nyckel. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](../x509certificate/getserialnumber/)() const | Hämtar serienummer från certifikatet som en byte-array. |
| virtual [String](../../system/string/) [GetSerialNumberString](../x509certificate/getserialnumberstring/)() const | Hämtar serienummer från certifikatet som en hexadecimal sträng. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importerar information från den angivna certifikatfilen. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importerar information från den angivna certifikatfilen. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importerar information från de angivna certifikatdata. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importerar information från de angivna certifikatdata. |
| void [Import](./import/)(const [String](../../system/string/)\&) override | Importerar information från den angivna certifikatfilen. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | Importerar information från den angivna certifikatdata. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objektet. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [X509Certificate](../x509certificate/)\& [operator=](../x509certificate/operator_equal/)(const [X509Certificate](../x509certificate/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar faktiskt ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [Reset](./reset/)() override | Återställer certifikatets tillstånd. |
| void [set_Archived](./set_archived/)(**bool**) const | Ställer in ett värde som indikerar att certifikatet är arkiverat. |
| void [set_FriendlyName](./set_friendlyname/)(const [String](../../system/string/)\&) | Ställer in certifikatets vänliga namn. |
| void [set_PrivateKey](./set_privatekey/)(const [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) | Ställer in eller rensar privat nyckel som är associerad med certifikatet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te templatargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)(**bool**) const override | Returnerar certifikatinformation i textformat. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returnerar certifikatinformation i textformat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| **bool** [Verify](./verify/)() const | Verifierar certifikatkedjan. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [X509Certificate](../x509certificate/)\&) |  |
|  [X509Certificate](../x509certificate/x509certificate/)() | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](../x509certificate/x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)() | Konstruerar tom [X509Certificate2](./). |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate2](./x509certificate2/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |
## Se även

* Klass [X509Certificate](../x509certificate/)
* Namnrymd [System::Security::Cryptography::X509Certificates](../)
* Bibliotek [Aspose.Slides](../../)