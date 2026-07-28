---
title: X509Certificate2
second_title: Aspose.Slides C++ API Referencia
description: "X509 tanúsítványt képvisel. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stack-en vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként való átadásához."
type: docs
weight: 40
url: /hu/system.security.cryptography.x509certificates/x509certificate2/
---
## X509Certificate2 osztály

X509 tanúsítványt képvisel. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stack-en vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be az osztályt [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként való továbbadáshoz.

```cpp
class X509Certificate2 : public System::Security::Cryptography::X509Certificates::X509Certificate
```

## Metódusok

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromCertFile](../x509certificate/createfromcertfile/)(const [String](../../system/string/)\&) | Létrehoz tanúsítványt a megadott PKCS7 fájlból. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\> [CreateFromSignedFile](../x509certificate/createfromsignedfile/)(const [String](../../system/string/)\&) | Létrehoz tanúsítványt a megadott aláírt fájlból. |
| void [Dispose](../x509certificate/dispose/)() override | Nem csinál semmit. |
| **bool** [Equals](../x509certificate/equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Két tanúsítványt összehasonlít. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/)) const | Exportálja a jelenlegi objektumot bájttömbbe a megadott formátum használatával. NEM VALÓSÍTOTT. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Exportálja a jelenlegi objektumot bájttömbbe a megadott formátum használatával. NEM VALÓSÍTOTT. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](../x509certificate/export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Exportálja a jelenlegi objektumot bájttömbbe a megadott formátum használatával. NEM VALÓSÍTOTT. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| **bool** [get_Archived](./get_archived/)() const | Visszaad egy értéket, amely jelzi, hogy a tanúsítvány archivált. |
| [X509ExtensionCollectionPtr](../x509extensioncollectionptr/) [get_Extensions](./get_extensions/)() const | Visszaad a tanúsítványhoz kapcsolódó kiegészítő objektumok gyűjteményét. |
| [String](../../system/string/) [get_FriendlyName](./get_friendlyname/)() const | Visszaad a tanúsítvány barátságos nevét. |
| IntPtr [get_Handle](../x509certificate/get_handle/)() const | Visszaad egy kezelőt a Microsoft Cryptographic API tanúsítványkörnyezethez. |
| **bool** [get_HasPrivateKey](./get_hasprivatekey/)() const | Ellenőrzi, hogy a tanúsítvány rendelkezik-e privát kulccsal. |
| [String](../../system/string/) [get_Issuer](../x509certificate/get_issuer/)() const | Visszaad a X.509v3 tanúsítványt kiállító hitelesítő hatóság nevét. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_IssuerName](./get_issuername/)() const | Visszaad a tanúsítványt kiállító fél nevét. |
| [DateTime](../../system/datetime/) [get_NotAfter](./get_notafter/)() const | Visszaad a helyi dátumot és időt, amely után a tanúsítvány már nem érvényes. |
| [DateTime](../../system/datetime/) [get_NotBefore](./get_notbefore/)() const | Visszaad a helyi dátumot és időt, amikor a tanúsítvány érvényessé válik. |
| [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\> [get_PrivateKey](./get_privatekey/)() const | Visszaad a tanúsítványhoz kapcsolódó privát kulcsot. |
| [SharedPtr](../../system/sharedptr/)\<[PublicKey](../publickey/)\> [get_PublicKey](./get_publickey/)() const | Visszaad egy tanúsítvány [PublicKey](../publickey/) objektumot. |
| [ByteArrayPtr](../../system/bytearrayptr/) [get_RawData](./get_rawdata/)() const | Visszaad a tanúsítvány nyers adatát. |
| [String](../../system/string/) [get_SerialNumber](./get_serialnumber/)() const | Visszaad egy tanúsítvány sorozatszámát. |
| [SharedPtr](../../system/sharedptr/)\<[Oid](../../system.security.cryptography/oid/)\> [get_SignatureAlgorithm](./get_signaturealgorithm/)() const | Visszaad a tanúsítvány aláírásához használt algoritmust. |
| [String](../../system/string/) [get_Subject](../x509certificate/get_subject/)() const | Visszaad a tanúsítvány alanyának megkülönböztetett nevét. |
| [SharedPtr](../../system/sharedptr/)\<[X500DistinguishedName](../x500distinguishedname/)\> [get_SubjectName](./get_subjectname/)() const | Visszaad a tanúsítvány alanyának nevét. |
| [String](../../system/string/) [get_Thumbprint](./get_thumbprint/)() const | Visszaad a tanúsítvány ujjlenyomatát. |
| **int32_t** [get_Version](./get_version/)() const | Visszaad a tanúsítvány formátum verzióját. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Visszaad a megadott bájttömbben lévő tanúsítvány típusát. |
| static [X509ContentType](../x509contenttype/) [GetCertContentType](./getcertcontenttype/)(const [String](../../system/string/)\&) | Visszaad a megadott fájlban lévő tanúsítvány típusát. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)() const | Visszaad a jelenlegi objektum hash-ét bájt tömbként. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](../x509certificate/getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Visszaad a jelenlegi objektum hash-ét bájt tömbként. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)() const | Visszaad a [SHA1](../../system.security.cryptography/sha1/) hash-t a jelenlegi objektumhoz hexadecimális stringként. |
| virtual [String](../../system/string/) [GetCertHashString](../x509certificate/getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Visszaad a [SHA1](../../system.security.cryptography/sha1/) hash-t a jelenlegi objektumhoz hexadecimális stringként. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaad az objektumhoz kapcsolódó referenciacsökkentő adatstruktúrát. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPrivateKey](./getdsaprivatekey/)() const | Visszaad a [RSA](../../system.security.cryptography/rsa/) privát kulcsot. |
| [SharedPtr](../../system/sharedptr/)\<[DSA](../../system.security.cryptography/dsa/)\> [GetDSAPublicKey](./getdsapublickey/)() const | Visszaad a [RSA](../../system.security.cryptography/rsa/) nyilvános kulcsot. |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPrivateKey](./getecdsaprivatekey/)() const | Visszaad a [RSA](../../system.security.cryptography/rsa/) privát kulcsot. |
| [SharedPtr](../../system/sharedptr/)\<[ECDsa](../../system.security.cryptography/ecdsa/)\> [GetECDsaPublicKey](./getecdsapublickey/)() const | Visszaad a [RSA](../../system.security.cryptography/rsa/) nyilvános kulcsot. |
| virtual [String](../../system/string/) [GetEffectiveDateString](../x509certificate/geteffectivedatestring/)() const | Visszaad a jelenlegi tanúsítvány hatálybalépési dátumát. |
| virtual [String](../../system/string/) [GetExpirationDateString](../x509certificate/getexpirationdatestring/)() const | Visszaad a jelenlegi tanúsítvány lejárati dátumát. |
| virtual [String](../../system/string/) [GetFormat](../x509certificate/getformat/)() const | Visszaad a tanúsítvány formátum nevét. |
| **int32_t** [GetHashCode](../x509certificate/gethashcode/)() const override | Visszaad a tanúsítvány hash kódját. |
| virtual [String](../../system/string/) [GetIssuerName](../x509certificate/getissuername/)() const | Visszaad a jelenlegi tanúsítványt kiállító hitelesítő hatóság nevét. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](../x509certificate/getkeyalgorithm/)() const | Visszaad a jelenlegi tanúsítvány kulcsinformációit stringként. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](../x509certificate/getkeyalgorithmparameters/)() const | Visszaad a jelenlegi tanúsítvány kulcsinformációit bájt tömbként. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](../x509certificate/getkeyalgorithmparametersstring/)() const | Visszaad a jelenlegi tanúsítvány kulcsinformációit hexadecimális stringként. |
| virtual [String](../../system/string/) [GetName](../x509certificate/getname/)() const | Visszaad a főszereplő nevét, akinek a jelenlegi tanúsítvány ki lett adva. |
| [String](../../system/string/) [GetNameInfo](./getnameinfo/)([X509NameType](../x509nametype/), **bool**) const | Visszaad a tanúsítvány alany vagy kibocsátó nevét. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](../x509certificate/getpublickey/)() const | Visszaad a tanúsítvány nyilvános kulcsát bájt tömbként. |
| virtual [String](../../system/string/) [GetPublicKeyString](../x509certificate/getpublickeystring/)() const | Visszaad a tanúsítvány nyilvános kulcsát hexadecimális stringként. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](../x509certificate/getrawcertdata/)() const | Visszaad a tanúsítvány nyers adatát bájt tömbként. |
| virtual [String](../../system/string/) [GetRawCertDataString](../x509certificate/getrawcertdatastring/)() const | Visszaad a tanúsítvány nyers adatát hexadecimális stringként. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPrivateKey](./getrsaprivatekey/)() const | Visszaad a [RSA](../../system.security.cryptography/rsa/) privát kulcsot. |
| [SharedPtr](../../system/sharedptr/)\<[RSA](../../system.security.cryptography/rsa/)\> [GetRSAPublicKey](./getrsapublickey/)() const | Visszaad a [RSA](../../system.security.cryptography/rsa/) nyilvános kulcsot. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](../x509certificate/getserialnumber/)() const | Visszaad a tanúsítvány sorozatszámát bájt tömbként. |
| virtual [String](../../system/string/) [GetSerialNumberString](../x509certificate/getserialnumberstring/)() const | Visszaad a tanúsítvány sorozatszámát hexadecimális stringként. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaad az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importálja az információkat a megadott tanúsítványfájlból. |
| void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importálja az információkat a megadott tanúsítványfájlból. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importálja az információkat a megadott tanúsítvány adatból. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) override | Importálja az információkat a megadott tanúsítvány adatból. |
| void [Import](./import/)(const [String](../../system/string/)\&) override | Importálja az információkat a megadott tanúsítványfájlból. |
| void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) override | Importálja az információkat a megadott tanúsítvány adatból. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum olyan típusú példány-e, amelyet a targetType leír. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és engedélyezi az alosztályok másolásos konstrukcióját. |
| [X509Certificate](../x509certificate/)\& [operator=](../x509certificate/operator_equal/)(const [X509Certificate](../x509certificate/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában nem másol semmit, csak új objektumot inicializál és engedélyezi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja az értéktípusú objektumot a nullptr-lal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [Reset](./reset/)() override | Visszaállítja a tanúsítvány állapotát. |
| void [set_Archived](./set_archived/)(**bool**) const | Beállít egy értéket, amely jelzi, hogy a tanúsítvány archivált. |
| void [set_FriendlyName](./set_friendlyname/)(const [String](../../system/string/)\&) | Beállítja a tanúsítvány barátságos nevét. |
| void [set_PrivateKey](./set_privatekey/)(const [SharedPtr](../../system/sharedptr/)\<[AsymmetricAlgorithm](../../system.security.cryptography/asymmetricalgorithm/)\>\&) | Beállítja vagy törli a tanúsítványhoz kapcsolódó privát kulcsot. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonparamétert gyenge mutatóként (nem megosztott). Lehetővé teszi a mutatók konténerben történő gyengére váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaad a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| [String](../../system/string/) [ToString](./tostring/)(**bool**) const override | Visszaadja a tanúsítvány információit szövegformátumban. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Visszaadja a tanúsítvány információit szövegformátumban. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| **bool** [Verify](./verify/)() const | Ellenőrzi a tanúsítványláncot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
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
|  [X509Certificate2](./x509certificate2/)() | Létrehoz egy üres [X509Certificate2](./)-t. |
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
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [X509Certificate](../x509certificate/)
* Névtér [System::Security::Cryptography::X509Certificates](../)
* Könyvtár [Aspose.Slides](../../)