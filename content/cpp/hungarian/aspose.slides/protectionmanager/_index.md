---
title: ProtectionManager
second_title: Aspose.Slides C++ API referenciája
description: Bemutató jelszóvédelem kezelése.
type: docs
weight: 4915
url: /hu/aspose.slides/protectionmanager/
---
## ProtectionManager osztály

[Presentation](../presentation/) jelszóvédelem kezelése.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | Megállapítja, hogy a bemutató jelszóval védett-e a módosításhoz. |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | A(z) [Presentation](../presentation/) titkosítja a megadott jelszóval. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze az objektumokat. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célra. |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | Ez a tulajdonság értelmes, ha a bemutató jelszóval védett. Ha igaz, akkor a dokumentumtulajdonságok titkosítva vannak a bemutató fájlban. Ha hamis, akkor a dokumentumtulajdonságok nyilvánosak, míg a bemutató titkosított. Read **bool**. |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | Lekéri a jelszót, amelyet a bemutató titkosításához használnak. Read-only [System::String](../../system/string/). |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | Lekéri az értéket, amely jelzi, hogy ez az példány titkosított-e. Read-only **bool**. |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | Ez a tulajdonság értelmes, ha a bemutatófájl jelszóval védett és a fájl dokumentumtulajdonságai nyilvánosak. Az igaz érték azt jelenti, hogy csak a dokumentumtulajdonságok töltődnek be egy titkosított bemutatófájlból jelszó használata nélkül. A hamis érték azt jelenti, hogy a teljes titkosított bemutató betöltődik a megfelelő jelszó használatával, nem csak a dokumentumtulajdonságok. Ha a bemutató nincs titkosítva, akkor a tulajdonság értéke mindig hamis. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak, akkor a tulajdonság értéke mindig hamis. Ha a Presentation.EncryptDocumentProperties igaz, akkor az IsOnlyDocumentPropertiesLoaded tulajdonság értéke mindig hamis. Read-only **bool**. |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | Lekéri az értéket, amely jelzi, hogy ez a bemutató írásvédett-e. Read-only **bool**. |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | Lekéri az írásvédett ajánlást. Read **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyéni objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrszem objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia szerint hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja össze az értéktípusú objektumot a nullptr-tal. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [RemoveEncryption](./removeencryption/)() override | Eltávolítja a titkosítást. |
| void [RemoveWriteProtection](./removewriteprotection/)() override | Eltávolítja az írásvédelmet a bemutatóról. |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | Ez a tulajdonság értelmes, ha a bemutató jelszóval védett. Ha igaz, akkor a dokumentumtulajdonságok titkosítva vannak a bemutató fájlban. Ha hamis, akkor a dokumentumtulajdonságok nyilvánosak, míg a bemutató titkosított. Write **bool**. |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | Beállítja az írásvédett ajánlást. Write **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (nem megosztottá) állítja. Lehetővé teszi a mutatók konténerben való gyenge módra váltását. |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | Beállítja az írásvédelmet a bemutatóhoz a megadott jelszóval. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrszem objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IProtectionManager](../iprotectionmanager/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)