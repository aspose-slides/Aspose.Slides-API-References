---
title: X509Certificate
second_title: Aspose.Slides for C++ API Referenciája
description: "X.509 v.3 tanúsítvány. Titkosított tanúsítványok nem támogatottak. Csak az X509KeyStorageFlags::DefaultKeySet jelző támogatott. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként."
type: docs
weight: 27
url: /hu/system.security.cryptography.x509certificates/x509certificate/
---
## X509Certificate osztály

X.509 v.3 tanúsítvány. Titkosított tanúsítványok nem támogatottak. Csak a [X509KeyStorageFlags::DefaultKeySet](../x509keystorageflags/) jelző támogatott. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad létrehozni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az új operátorral, mivel ez futásidejű hibákhoz és/vagy állítási hibákhoz vezet. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként.

```cpp
class X509Certificate : public virtual System::Object,
                        public System::IDisposable
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromCertFile](./createfromcertfile/)(const [String](../../system/string/)\&) | Létrehoz tanúsítványt a megadott PKCS7 fájlból. |
| static [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\> [CreateFromSignedFile](./createfromsignedfile/)(const [String](../../system/string/)\&) | Létrehoz tanúsítványt a megadott aláírt fájlból. |
| void [Dispose](./dispose/)() override | Nem csinál semmit. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Két tanúsítványt hasonlít össze. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/)) const | Exportálja a jelenlegi objektumot egy bájt tömbbe a megadott formátummal. NEM KIVITELEZETT. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [SecureStringPtr](../../system.security/securestringptr/)\&) const | Exportálja a jelenlegi objektumot egy bájt tömbbe a megadott formátummal. NEM KIVITELEZETT. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [Export](./export/)([X509ContentType](../x509contenttype/), const [String](../../system/string/)\&) const | Exportálja a jelenlegi objektumot egy bájt tömbbe a megadott formátummal. NEM KIVITELEZETT. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célra. |
| IntPtr [get_Handle](./get_handle/)() const | Visszaad egy kezelőt a Microsoft Cryptographic API tanúsítványkörnyezethez. |
| [String](../../system/string/) [get_Issuer](./get_issuer/)() const | Visszaadja az X.509v3 tanúsítványt kibocsátó hatóság nevét. |
| [String](../../system/string/) [get_Subject](./get_subject/)() const | Visszaadja a tanúsítvány alanyának megkülönböztetett nevét. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)() const | Visszaadja a jelenlegi objektum hash-ét bájt tömbként. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetCertHash](./getcerthash/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Visszaadja a jelenlegi objektum hash-ét bájt tömbként. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)() const | Visszaadja a [SHA1](../../system.security.cryptography/sha1/) hash-t a jelenlegi objektumhoz hexadecimális karakterláncként. |
| virtual [String](../../system/string/) [GetCertHashString](./getcerthashstring/)(const [HashAlgorithmName](../../system.security.cryptography/hashalgorithmname/)\&) const | Visszaadja a [SHA1](../../system.security.cryptography/sha1/) hash-t a jelenlegi objektumhoz hexadecimális karakterláncként. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz tartozó referencia számláló adatstruktúrát. |
| virtual [String](../../system/string/) [GetEffectiveDateString](./geteffectivedatestring/)() const | Visszaadja a jelenlegi tanúsítvány hatályba lépési dátumát. |
| virtual [String](../../system/string/) [GetExpirationDateString](./getexpirationdatestring/)() const | Visszaadja a jelenlegi tanúsítvány lejárati dátumát. |
| virtual [String](../../system/string/) [GetFormat](./getformat/)() const | Visszaadja a tanúsítvány formátumának nevét. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Visszaadja a tanúsítvány hash-kódját. |
| virtual [String](../../system/string/) [GetIssuerName](./getissuername/)() const | Visszaadja a jelenlegi tanúsítványt kibocsátó hitelesítő hatóság nevét. |
| virtual [String](../../system/string/) [GetKeyAlgorithm](./getkeyalgorithm/)() const | Visszaadja a jelenlegi tanúsítvány kulcsinformációit karakterláncként. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetKeyAlgorithmParameters](./getkeyalgorithmparameters/)() const | Visszaadja a jelenlegi tanúsítvány kulcsinformációit bájt tömbként. |
| virtual [String](../../system/string/) [GetKeyAlgorithmParametersString](./getkeyalgorithmparametersstring/)() const | Visszaadja a jelenlegi tanúsítvány kulcsinformációit hexadecimális karakterláncként. |
| virtual [String](../../system/string/) [GetName](./getname/)() const | Visszaadja a jelenlegi tanúsítvány kibocsátójának nevét. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetPublicKey](./getpublickey/)() const | Visszaadja a tanúsítvány nyilvános kulcsát bájt tömbként. |
| virtual [String](../../system/string/) [GetPublicKeyString](./getpublickeystring/)() const | Visszaadja a tanúsítvány nyilvános kulcsát hexadecimális karakterláncként. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetRawCertData](./getrawcertdata/)() const | Visszaadja a tanúsítvány nyers adatait bájt tömbként. |
| virtual [String](../../system/string/) [GetRawCertDataString](./getrawcertdatastring/)() const | Visszaadja a tanúsítvány nyers adatait hexadecimális karakterláncként. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [GetSerialNumber](./getserialnumber/)() const | Visszaadja a tanúsítvány sorozatszámát bájt tömbként. |
| virtual [String](../../system/string/) [GetSerialNumberString](./getserialnumberstring/)() const | Visszaadja a tanúsítvány sorozatszámát hexadecimális karakterláncként. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importálja az információt a megadott tanúsítványfájlból. NEM KIVITELEZETT. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importálja az információt a megadott tanúsítványfájlból. NEM KIVITELEZETT. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importálja az információt a megadott tanúsítványfájlból. NEM KIVITELEZETT. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Importálja az információt a megadott tanúsítványfájlból. NEM KIVITELEZETT. |
| virtual void [Import](./import/)(const [String](../../system/string/)\&) | Importálja az információt a megadott tanúsítványfájlból. NEM KIVITELEZETT. |
| virtual void [Import](./import/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Importálja az információt a megadott tanúsítványfájlból. NEM KIVITELEZETT. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) megfigyelő objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializál minden belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [X509Certificate](./)\& [operator=](./operator_equal/)(const [X509Certificate](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [Reset](./reset/)() | Visszaállítja a tanúsítvány állapotát. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a shared helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](./tostring/)(**bool**) const | Visszaadja a tanúsítvány információkat szöveges formátumban. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Visszaadja a tanúsítvány információkat szöveges formátumban. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) megfigyelő objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [X509Certificate](./x509certificate/)(const [X509Certificate](./)\&) |  |
|  [X509Certificate](./x509certificate/)() | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate](./)\>\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [String](../../system/string/)\&, const [SecureStringPtr](../../system.security/securestringptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
|  [X509Certificate](./x509certificate/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, [X509KeyStorageFlags](../x509keystorageflags/)) | Konstruktor. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Ptr](./ptr/) | Mutató típus. |

## Lásd még

* Osztály [Object](../../system/object/)
* Osztály [IDisposable](../../system/idisposable/)
* Névtér [System::Security::Cryptography::X509Certificates](../)
* Könyvtár [Aspose.Slides](../../)