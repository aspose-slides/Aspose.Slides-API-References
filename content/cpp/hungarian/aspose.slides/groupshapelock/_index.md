---
title: GroupShapeLock
second_title: Aspose.Slides C++ API-referencia
description: Megállapítja, hogy a szülő GroupShape mely műveletei vannak letiltva.
type: docs
weight: 1210
url: /hu/aspose.slides/groupshapelock/
---
## GroupShapeLock osztály

Megállapítja, hogy a szülő [GroupShape](../groupshape/) mely műveletei vannak letiltva.

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek számít, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek számít, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Megállapítja, hogy az alakzatnak meg kell-e őriznie az arányt a méretezés során. Olvasás: **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Megállapítja, hogy a forma csoportba való hozzáadása tiltott-e. Olvasás: **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Igaz értéket ad vissza, ha minden zárolási jelző le van tiltva. Csak olvasható **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Megállapítja, hogy a forma mozgatása tiltott-e. Olvasás: **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Megállapítja, hogy a forma forgásszögének módosítása tiltott-e. Olvasás: **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Megállapítja, hogy a forma kiválasztása tiltott-e. Olvasás: **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Megállapítja, hogy a forma átméretezése tiltott-e. Olvasás: **bool**. |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | Megállapítja, hogy a csoportos alakzat felosztása tiltott-e. Olvasás: **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktálását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstruktálását. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Megállapítja, hogy az alakzatnak meg kell-e őriznie az arányt a méretezés során. Írás: **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Megállapítja, hogy a forma csoportba való hozzáadása tiltott-e. Írás: **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Megállapítja, hogy a forma mozgatása tiltott-e. Írás: **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Megállapítja, hogy a forma forgásszögének módosítása tiltott-e. Írás: **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Megállapítja, hogy a forma kiválasztása tiltott-e. Írás: **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Megállapítja, hogy a forma átméretezése tiltott-e. Írás: **bool**. |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | Megállapítja, hogy a csoportos alakzat felosztása tiltott-e. Írás: **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá (a megosztott helyett) állítja be. Lehetővé teszi a mutatók tárolókban való gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül meghívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [BaseShapeLock](../baseshapelock/)
* Osztály [IGroupShapeLock](../igroupshapelock/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)