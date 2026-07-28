---
title: IdnMapping
second_title: Aspose.Slides C++ API Referencia
description: "Az IdnMapping a nevek Punycode-ra való leképezésére szolgál. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stackben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményezhet. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és ezt a mutatót használja a függvények argumentumaként való átadásra."
type: docs
weight: 170
url: /hu/system.globalization/idnmapping/
---
## IdnMapping osztály


[IdnMapping](./) a nevek Punycode-ra történő leképezésére szolgál. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stackben vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és ezt a mutatót használja a függvények argumentumaként való átadásra.

```cpp
class IdnMapping : public System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Összehasonlít két [IdnMapping](./) objektumot. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlít objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlít referencia típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **bool** [get_AllowUnassigned](./get_allowunassigned/)() const | Lekéri a jelzőt, amely jelzi, hogy a műveletekben hozzárendelés nélküli kódpontok használatosak-e. |
| **bool** [get_UseStd3AsciiRules](./get_usestd3asciirules/)() const | Lekéri a jelzőt, amely jelzi, hogy a műveletekben szabványos elnevezési konvenciók használatosak-e. |
| [String](../../system/string/) [GetAscii](./getascii/)(const [String](../../system/string/)\&) const | [Convert](../../system/convert/) unicode domain név ascii megfelelőjéhez. |
| [String](../../system/string/) [GetAscii](./getascii/)(const [String](../../system/string/)\&, int) const | [Convert](../../system/convert/) unicode domain név ascii megfelelőjéhez. |
| [String](../../system/string/) [GetAscii](./getascii/)(const [String](../../system/string/)\&, int, int) const | [Convert](../../system/convert/) unicode domain név ascii megfelelőjéhez. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referenciaszámláló adatstruktúrát. |
| int [GetHashCode](./gethashcode/)() const override | Lekéri az aktuális [IdnMapping](./) objektum hash kódját. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| [String](../../system/string/) [GetUnicode](./getunicode/)(const [String](../../system/string/)\&) const | [Convert](../../system/convert/) ascii domain név unicode megfelelőjéhez. |
| [String](../../system/string/) [GetUnicode](./getunicode/)(const [String](../../system/string/)\&, int) const | [Convert](../../system/convert/) ascii domain név unicode megfelelőjéhez. |
| [String](../../system/string/) [GetUnicode](./getunicode/)(const [String](../../system/string/)\&, int, int) const | [Convert](../../system/convert/) ascii domain név unicode megfelelőjéhez. |
|  [IdnMapping](./idnmapping/)() | RTTI információ. |
|  [IdnMapping](./idnmapping/)(const [IdnMapping](./)\&) |  |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) megfigyelő objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehoz egy objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [IdnMapping](./)\& [operator=](./operator_equal/)(const [IdnMapping](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignációs operátor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlít objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlít objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_AllowUnassigned](./set_allowunassigned/)(**bool**) | Beállítja a jelzőt, amely jelzi, hogy a műveletekben hozzárendelés nélküli kódpontok használatosak-e. |
| void [set_UseStd3AsciiRules](./set_usestd3asciirules/)(**bool**) | Beállítja a jelzőt, amely jelzi, hogy a műveletekben szabványos elnevezési konvenciók használatosak-e. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) szerkezetet. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül, vagy használja a [LockContext](../../system/lockcontext/) megfigyelő objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névterület [System::Globalization](../)
* Könyvtár [Aspose.Slides](../../)