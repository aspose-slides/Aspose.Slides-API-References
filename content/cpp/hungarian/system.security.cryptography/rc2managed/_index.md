---
title: RC2Managed
second_title: Aspose.Slides C++ API Referencia
description: "Kezelt RC2 algoritmus. Csak az ECB, CFB és CBC titkosítási módok támogatottak. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy a new operátor használatával, mivel ez futási hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként történő átadásra."
type: docs
weight: 378
url: /hu/system.security.cryptography/rc2managed/
---
## RC2Managed osztály

Kezelt [RC2](../rc2/) algoritmus. Csak az ECB, CFB és CBC titkosítási módok támogatottak. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy a new operátorral, mivel ez futási hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót az argumentumként történő függvényhívásokhoz.

```cpp
class RC2Managed : public System::Security::Cryptography::RC2
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | Létrehozza az algoritmus példányát. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Létrehozza a dekódoló objektumot explicit paraméterekkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | Létrehozza a dekódoló objektumot az algoritmus objektum által definiált paraméterekkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Létrehozza a dekódoló objektumot az algoritmus objektum által definiált paraméterekkel. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Létrehozza a titkosító objektumot explicit paraméterekkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | Létrehozza a titkosító objektumot az algoritmus objektum által definiált paraméterekkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Létrehozza a titkosító objektumot az algoritmus objektum által definiált paraméterekkel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol a két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semelyik értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| void [GenerateIV](./generateiv/)() override | Létrehozza egy véletlenszerű kezdeti értéket, és tárolja az algoritmus belső részeiben. |
| void [GenerateKey](./generatekey/)() override | Létrehozza egy véletlenszerű kulcsot, és tárolja az algoritmus belső részeiben. |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | Lekéri a kriptográfiai művelet blokk méretét. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | Lekéri a kriptográfiai művelet visszacsatolás méretét. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | Lekéri a kriptográfiai művelet kezdeti értékét. Újat hoz létre, ha még nem létezik. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | Lekéri a kriptográfiai művelet kulcsát. Újat hoz létre, ha még nem létezik. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | Lekéri a kriptográfiai művelet kulcsméretét. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | Lekéri a kriptográfiai művelet módját. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | Lekéri a kriptográfiai művelet kitöltését. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri a objektumhoz társított referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típusú példány-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásalapú konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásalapú konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | Beállítja a kriptográfiai művelet blokk méretét. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | Beállítja a kriptográfiai művelet visszacsatolás méretét. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Beállítja a kriptográfiai művelet kezdeti értékét. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Beállítja a kriptográfiai művelet kulcsát. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | Beállítja a kriptográfiai művelet kulcsméretét. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | Beállítja a kriptográfiai művelet módját. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | Beállítja a kriptográfiai művelet kitöltését. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablon argumentumot gyenge mutatóként (a shared helyett). Lehetővé teszi a mutatók átkapcsolását gyenge módba a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) kifejezést. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | Ellenőrzi, hogy a kulcsméret érvényes-e. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [RC2](../rc2/)
* Névtere [System::Security::Cryptography](../)
* Könyvtár [Aspose.Slides](../../)