---
title: IGroupShapeLock
second_title: Aspose.Slides C++ API-referencia
description: Meghatározza, hogy a szülő GroupShape mely műveletei vannak letiltva.
type: docs
weight: 2497
url: /hu/aspose.slides/igroupshapelock/
---
## IGroupShapeLock osztály


Determines which operations are disabled on the parent [GroupShape](../groupshape/).

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze a C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | A C#-stílusú lebegőpontos összehasonlítást emulálja, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Meghatározza, hogy a shape megőrizze-e a képarányt átméretezéskor. Olvasás **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Meghatározza, hogy a shape hozzáadása egy csoporthoz tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Igaz értéket ad vissza, ha minden lock-flag le van tiltva. Csak olvasható **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Meghatározza, hogy a shape mozgatása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Meghatározza, hogy a shape forgatási szöge módosítása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Meghatározza, hogy a shape kiválasztása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Meghatározza, hogy a shape méretezése tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | Meghatározza, hogy a groupshape felbontása tiltott-e. Olvasás **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi a származtatott osztályok másolását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi a származtatott osztályok másolását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia összehasonlítja az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Meghatározza, hogy a shape megőrizze-e a képarányt átméretezéskor. Írás **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Meghatározza, hogy a shape hozzáadása egy csoporthoz tiltott-e. Írás **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Meghatározza, hogy a shape mozgatása tiltott-e. Írás **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Meghatározza, hogy a shape forgatási szöge módosítása tiltott-e. Írás **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Meghatározza, hogy a shape kiválasztása tiltott-e. Írás **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Meghatározza, hogy a shape méretezése tiltott-e. Írás **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | Meghatározza, hogy a groupshape felbontása tiltott-e. Írás **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók tartályokban történő átváltását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Megkapja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IBaseShapeLock](../ibaseshapelock/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)