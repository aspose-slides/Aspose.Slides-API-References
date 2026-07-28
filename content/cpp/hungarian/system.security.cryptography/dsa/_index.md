---
title: DSA
second_title: Aspose.Slides C++ API referenciája
description: "Alaposztály a DSA algoritmus implementációihoz. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy a new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 131
url: /hu/system.security.cryptography/dsa/
---
## DSA osztály

Alaposztály a [DSA](./) algoritmus implementációihoz. Az osztály objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy a new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek.

```cpp
class DSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Felszabadítja az összes erőforrást. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)() | Létrehozza az alapértelmezett [DSA](./) algoritmus implementációt. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Létrehozza az alapértelmezett [DSA](./) algoritmus implementációt. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)(**int32_t**) | Létrehozza az alapértelmezett [DSA](./) algoritmus implementációt a megadott kulcsmérettel. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [Create](./create/)(const [DSAParameters](../dsaparameters/)\&) | Létrehozza az alapértelmezett [DSA](./) algoritmus implementációt a megadott paraméterekkel. |
| static [SharedPtr](../../system/sharedptr/)\<[DSA](./)\> [CreateFromXmlString](./createfromxmlstring/)(const [String](../../system/string/)\&) | Létrehozza az alapértelmezett [DSA](./) algoritmus implementációt a megadott XML-kódolt paraméterekkel. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [CreateSignature](./createsignature/)([ByteArrayPtr](../../system/bytearrayptr/)) | Létrehozza a [DSA](./) aláírást a megadott adatokhoz. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | Felszabadítja a jelenlegi objektum által birtokolt erőforrásokat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulálja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual [DSAParameters](../dsaparameters/) [ExportParameters](./exportparameters/)(**bool**) | Exportálja az összes paramétert. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| void [FromXmlString](./fromxmlstring/)([String](../../system/string/)) override | Inicializálja az objektumot XML-kódolt paraméterekkel. |
| virtual [String](../../system/string/) [get_KeyExchangeAlgorithm](../asymmetricalgorithm/get_keyexchangealgorithm/)() | Megkapja a használni kívánt kulcscsere algoritmust. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | Megkapja a kulcsméretet. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Megkapja az engedélyezett kulcsméretek tömbjét. |
| virtual [String](../../system/string/) [get_SignatureAlgorithm](../asymmetricalgorithm/get_signaturealgorithm/)() | Megkapja a használni kívánt aláírás algoritmust. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja a objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual void [ImportParameters](./importparameters/)([DSAParameters](../dsaparameters/)) | Importálja az összes paramétert az adatstruktúrából. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a megadott targetType által leírt típus példánya-e. A C# ‘is’ operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() állítás blokkolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) guard objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Engedélyezi egyedi típusok klónozását. |
| [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, valójában csak inicializálja az új objektumot és engedélyezi a származtatott osztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Nem másol semmit, valójában csak inicializálja az új objektumot és engedélyezi a származtatott osztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciaként. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciaként. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként összehasonlítja az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Beállítja a kulcsméretet. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablon argumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók átkapcsolását a gyenge módra a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmussal, és aláírja az eredményt. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | Kiszámítja a megadott adat tömb hash értékét a megadott hash algoritmussal, és aláírja az eredményt. |
| [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Kiszámítja a megadott bináris adatfolyam hash értékét a megadott hash algoritmussal, és aláírja az eredményt. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Engedélyezi az egyedi objektumok stringgé alakítását. |
| [String](../../system/string/) [ToXmlString](./toxmlstring/)(**bool**) override | Exportálja az összes paramétert XML formátumban. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() állítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) guard objektumot. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Ellenőrzi, hogy a megadott adat aláírása érvényes-e. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Ellenőrzi, hogy a megadott adat aláírása érvényes-e. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Ellenőrzi, hogy a megadott bináris adatfolyam aláírása érvényes-e. |
| virtual **bool** [VerifySignature](./verifysignature/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) | Ellenőrzi a [DSA](./) aláírást a megadott adatokra. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Névtér [System::Security::Cryptography](../)
* Könyvtár [Aspose.Slides](../../)