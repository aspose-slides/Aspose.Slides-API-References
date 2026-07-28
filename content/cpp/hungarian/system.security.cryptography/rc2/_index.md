---
title: RC2
second_title: Aspose.Slides C++ API referencia
description: "RC2 szimmetrikus algoritmus alaposztály. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként."
type: docs
weight: 365
url: /hu/system.security.cryptography/rc2/
---
## RC2 osztály

[RC2](./) szimmetrikus algoritmus alaposztály. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként.

```cpp
class RC2 : public System::Security::Cryptography::SymmetricAlgorithm
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | Algoritmuspéldányt hoz létre. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](../symmetricalgorithm/createdecryptor/)() | Dekódoló objektumot hoz létre a algoritmus objektumhoz kapcsolódó paraméterekkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](../symmetricalgorithm/createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Dekódolót hoz létre explicit paraméterekkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](../symmetricalgorithm/createencryptor/)() | Titkosítót hoz létre a algoritmus objektumhoz kapcsolódó paraméterekkel. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](../symmetricalgorithm/createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Titkosítót hoz létre explicit paraméterekkel. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szempontjából hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, noha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, noha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual void [GenerateIV](../symmetricalgorithm/generateiv/)() | Véletlenszerű kezdeti értéket generál az algoritmushoz. Felülírja a meglévőt (ha van). |
| virtual void [GenerateKey](../symmetricalgorithm/generatekey/)() | Véletlenszerű kulcsot generál az algoritmushoz. Felülírja a meglévőt (ha van). |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | A kriptográfiai művelet blokkméretét adja vissza. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | A kriptográfiai művelet visszacsatolási méretét adja vissza. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | A kriptográfiai művelet kezdeti értékét adja vissza. Újat hoz létre, ha még nem létezik. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | A kriptográfiai művelet kulcsát adja vissza. Újat hoz létre, ha még nem létezik. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | A kriptográfiai művelet kulcsméretét adja vissza. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | A kriptográfiai művelet módját adja vissza. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | A kriptográfiai művelet kitöltését adja vissza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | A objektumhoz kapcsolódó referenciacsounter adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacsountert a megadott értékkel. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | Beállítja a kriptográfiai művelet blokkméretét. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | Beállítja a kriptográfiai művelet visszacsatolási méretét. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Beállítja a kriptográfiai művelet kezdeti értékét. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Beállítja a kriptográfiai művelet kulcsát. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | Beállítja a kriptográfiai művelet kulcsméretét. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | Beállítja a kriptográfiai művelet módját. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | Beállítja a kriptográfiai művelet kitöltését. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonparamétert gyenge mutatóval (a shared helyett) állítja be. Lehetővé teszi a mutatók konténerekben való weak módra történő átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | A megosztott referenciacsounter aktuális értékét adja vissza. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsountert. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsountert. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | Ellenőrzi, hogy a kulcsméret érvényes-e. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsountert. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsountert. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Objektumot megsemmisíti. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [SymmetricAlgorithm](../symmetricalgorithm/)
* Névtér [System::Security::Cryptography](../)
* Könyvtár [Aspose.Slides](../../)