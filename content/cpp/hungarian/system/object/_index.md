---
title: Object
second_title: Aspose.Slides C++ API referencia
description: Alaposztály, amely lehetővé teszi a System.Object osztályban elérhető metódusok használatát C#-ban. Minden nem triviális osztálynak, amely a lefordított környezetben használatos, öröklődnie kell.
type: docs
weight: 1132
url: /hu/system/object/
---
## Objektumosztály

Alaposztály, amely lehetővé teszi a [System.Object](./) osztályban elérhető módszerek használatát C#-ban. Minden nem triviális osztálynak, amely a lefordított környezetben használatos, öröklődnie kell.

```cpp
class Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](./equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | A C# [Object.GetHashCode()](./gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](./gettype/) hívás analógiája. |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# „is” operátor analógiája. |
| void [Lock](./lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrzőobjektumot. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | A C# [Object.MemberwiseClone()](./memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](./object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](./object/)([Object](./) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Referenciával hasonlítja össze az objektumokat. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Referenciával hasonlítja össze az objektumokat. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Értéktípusú objektumot hasonlít össze a nullptr-re hivatkozva. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](./referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | A [Object::ReferenceEquals](./referenceequals/) specializációja a stringek esetére. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot egy gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konvertálását konténerekben gyenge módra. |
| int [SharedCount](./sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../string/) [ToString](./tostring/)() const | A C# [Object.ToString()](./tostring/) metódus analógiája. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Megvalósítja a C# typeof([System.Object](./)) konstrukciót. |
| void [Unlock](./unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](./weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](./~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [ptr](./ptr/) | Okos mutató típus álneve. |

## Megjegyzések

A C# [System.Object](./) osztályban elérhető módszerek mellett támogatja a lefordított kód környezetre jellemző koncepciókat is. Ez magában foglalja a okos mutató osztályok által használt referenciaszámlálást ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) és egyéb, a memória kezelésével, hibakereséssel stb. kapcsolatos szolgáltatásokat.

Minden [Object](./) két referenciaszámlálóval rendelkezik: megosztott referenciaszámlálóval és gyenge referenciaszámlálóval. A gyenge referenciaszámláló mindig egy leválasztott adatstruktúrában tárolódik, nem a [Object](./)-ban, ami lehetővé teszi, hogy a gyenge mutatók a hivatkozott objektum után is fennmaradjanak. Az okos referenciaszámláló vagy az objektumban, vagy ugyanabban a leválasztott struktúrában van tárolva, az ENABLE_EXTERNAL_REFCOUNT makró állapotától függően. Alapértelmezés szerint hibakereső (debug) buildben engedélyezett, kiadási (release) buildben letiltott. Ha az okos mutató számláló az objektumban tárolódik, a leválasztott adatstruktúra csak akkor jön létre, ha gyenge mutatók léteznek az objektumra. Ellenkező esetben az objektummal együtt jön létre.

Minden okos mutató ezeket a két referenciaszámlálót használja, és ugyanahhoz az egyetlen tulajdonosi csoporthoz járul hozzá.

Ha a [Object](./) alosztályt a stack-en hozza létre, nem hozhatók létre rá okos mutatók, egyébként stack törlési probléma merül fel.

Ez a típus vagy stack-en értéktípusként, vagy a heap-en a [System::MakeObject()](../makeobject/) függvény használatával allokálható. Miután az objektum allokálva van, soha ne keverje össze ezeket a két felhasználási esetet: [SmartPtr](../smartptr/) mutatók stack-en allokált objektumokra való hivatkozása szigorúan tilos.

## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)