---
title: DSACryptoServiceProvider
second_title: "Aspose.Slides C++ API referenciája"
description: "DSA algoritmus CSP formában. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményezhet. Mindig csomagolja ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként történő átadásához."
type: docs
weight: 144
url: /hu/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider osztály


[DSA](../dsa/) algoritmus CSP formában. Az osztály objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály függvényekhez argumentumként való átadásához.

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Felszabadítja az összes erőforrást. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)() | Létrehozza az alapértelmezett [DSA](../dsa/) algoritmus megvalósítását. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [String](../../system/string/)\&) | Létrehozza az alapértelmezett [DSA](../dsa/) algoritmus megvalósítását. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(**int32_t**) | Létrehozza az alapértelmezett [DSA](../dsa/) algoritmus megvalósítását a megadott kulcsmérettel. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [Create](../dsa/create/)(const [DSAParameters](../dsaparameters/)\&) | Létrehozza az alapértelmezett [DSA](../dsa/) algoritmus megvalósítását a megadott paraméterekkel. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](../dsa/)\> [CreateFromXmlString](../dsa/createfromxmlstring/)(const [String](../../system/string/)\&) | Létrehozza az alapértelmezett [DSA](../dsa/) algoritmus megvalósítását a megadott XML-kódolt paraméterekkel. |
| [ByteArrayPtr](../../system/bytearrayptr/) [CreateSignature](./createsignature/)([ByteArrayPtr](../../system/bytearrayptr/)) override | Létrehozza a [DSA](../dsa/) aláírást a megadott adatokhoz. |
| void [Dispose](./dispose/)() override | Felszabadítja az objektumhoz kapcsolódó adatokat. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | Konstruktor. Alapértelmezett paramétereket használ. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [DSAParameters](../dsaparameters/)\&) | Konstruktor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Konstruktor. Nincs megvalósítva. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**) | Konstruktor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(**int32_t**, const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Konstruktor. Nincs megvalósítva. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az érték típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| [ByteArrayPtr](../../system/bytearrayptr/) [ExportCspBlob](./exportcspblob/)(**bool**) override | Exportál egy blob-ot, amely kulcsinformációt tartalmaz. Nincs megvalósítva. |
| [DSAParameters](../dsaparameters/) [ExportParameters](./exportparameters/)(**bool**) override | Exportálja a CSP paramétereket. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| void [FromXmlString](../dsa/fromxmlstring/)([String](../../system/string/)) override | Inicializálja az objektumot XML-kódolt paraméterekkel. |
| [SharedPtr](../../system/sharedptr/)\<[CspKeyContainerInfo](../cspkeycontainerinfo/)\> [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Visszaad egy [CspKeyContainerInfo](../cspkeycontainerinfo/) objektumot. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Ellenőrzi az objektumhoz kapcsolódó kulcscsere algoritmust. |
| **int32_t** [get_KeySize](./get_keysize/)() override | Visszaadja a kulcs méretét. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Visszaad egy tömböt az engedélyezett kulcsméretekkel. |
| **bool** [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Ellenőrzi, hogy a kulcs tárolva van-e a CSP objektumban. |
| **bool** [get_PublicOnly](./get_publiconly/)() const | Ellenőrzi, hogy csak a nyilvános kulcs van-e jelen a CSP objektumban. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Visszaadja a használni kívánt aláírási algoritmust. |
| static **bool** [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Ellenőrzi, hogy a kulcs a gépi tárolóban, nem felhasználói tárolóban marad-e. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz tartozó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-ét. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| void [ImportCspBlob](./importcspblob/)([ByteArrayPtr](../../system/bytearrayptr/)) override | Importál egy blob-ot, amely kulcsinformációt tartalmaz. Nincs megvalósítva. |
| void [ImportParameters](./importparameters/)([DSAParameters](../dsaparameters/)) override | Importálja az összes paramétert az adatstruktúrából. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak egy új objektumot inicializál és lehetővé teszi a származtatott osztályok másolás-konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit sem másol, csak egy új objektumot inicializál és lehetővé teszi a származtatott osztályok másolás-konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítja az érték típusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Beállítja a kulcs méretét. |
| void [set_PersistKeyInCsp](./set_persistkeyincsp/)(**bool**) | Meghatározza, hogy a kulcs tárolva van-e a CSP objektumban. |
| static void [set_UseMachineKeyStore](./set_usemachinekeystore/)(**bool**) | Meghatározza, hogy a kulcs a gépi tárolóban, nem felhasználói tárolóban marad-e. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóként (nem megosztott) állítja be. Lehetővé teszi a mutatók konténerekben gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Kiszámítja a megadott bemeneti érték aláírását. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Kiszámítja a megadott bemeneti érték aláírását. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**) | Kiszámítja a megadott bemeneti érték aláírását. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Kiszámítja a megadott bináris adatfolyam hash értékét a megadott hash algoritmus használatával, és aláírja az eredményt. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&) | Kiszámítja a megadott bemeneti érték aláírását. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| [String](../../system/string/) [ToXmlString](../dsa/toxmlstring/)(**bool**) override | Exportálja az összes paramétert XML formátumban. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Ellenőrzi az adat aláírását. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Ellenőrzi, hogy a megadott adat aláírása érvényes-e. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Ellenőrzi, hogy a megadott adat aláírása érvényes-e. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Ellenőrzi, hogy a megadott bináris adatfolyam aláírása érvényes-e. |
| **bool** [VerifyHash](./verifyhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [String](../../system/string/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Ellenőrzi az adat aláírását. |
| **bool** [VerifySignature](./verifysignature/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) override | Ellenőrzi a [DSA](../dsa/) aláírást a megadott adatokra. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [DSA](../dsa/)
* Osztály [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Névtér [System::Security::Cryptography](../)
* Könyvtár [Aspose.Slides](../../)