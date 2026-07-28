---
title: AutoShapeLock
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogy mely műveletek vannak letiltva a szülő AutoshapeEx objektumon.
type: docs
weight: 79
url: /hu/aspose.slides/autoshapelock/
---
## AutoShapeLock osztály


Megállapítja, hogy milyen műveletek vannak letiltva a szülő AutoshapeEx objektumon.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## Módszerek

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat C# stílusban hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat C# stílusban hasonlít össze. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Megállapítja, hogy a beállítási értékek módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Megállapítja, hogy a nyílfejek módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Megállapítja, hogy a alakzatnak a méretezéskor meg kell-e őriznie az arányt. Olvas **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Megállapítja, hogy ennek az alakzatnak a körvonalának közvetlen módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Megállapítja, hogy ennek az alakzatnak a csoportba való felvétele tiltott-e. Olvas **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Igaz értéket ad vissza, ha minden zárolási jelző le van tiltva. Csak-olvasható **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Megállapítja, hogy ennek az alakzatnak a mozgatása tiltott-e. Olvas **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Megállapítja, hogy ennek az alakzatnak a forgatási szöge módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Megállapítja, hogy ennek az alakzatnak a kiválasztása tiltott-e. Olvas **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Megállapítja, hogy az alakzat típusának módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Megállapítja, hogy ennek az alakzatnak a méretezése tiltott-e. Olvas **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | Megállapítja, hogy a szöveg szerkesztése tiltott-e. Olvas **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őradobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és engedélyezi az alosztályok másolóképzését. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál, és engedélyezi az alosztályok másolóképzését. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlít össze értéktípusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Meghatározza, hogy a beállítási értékek módosítása tiltott-e. Ír **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Meghatározza, hogy a nyílfejek módosítása tiltott-e. Ír **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Meghatározza, hogy az alakzatnak a méretezéskor meg kell-e őriznie az arányt. Ír **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Meghatározza, hogy ennek az alakzatnak a körvonalának közvetlen módosítása tiltott-e. Ír **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Meghatározza, hogy ennek az alakzatnak a csoportba való felvétele tiltott-e. Ír **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Meghatározza, hogy ennek az alakzatnak a mozgatása tiltott-e. Ír **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Meghatározza, hogy ennek az alakzatnak a forgatási szöge módosítása tiltott-e. Ír **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Meghatározza, hogy ennek az alakzatnak a kiválasztása tiltott-e. Ír **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Meghatározza, hogy az alakzat típusának módosítása tiltott-e. Ír **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Meghatározza, hogy ennek az alakzatnak a méretezése tiltott-e. Ír **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | Meghatározza, hogy a szöveg szerkesztése tiltott-e. Ír **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | A n-edik sablonargumentumot gyenge mutatóvá állítja (a shared helyett). Lehetővé teszi a mutatók konténerekben történő gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őradobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okosmutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [BaseShapeLock](../baseshapelock/)
* Osztály [IAutoShapeLock](../iautoshapelock/)
* Névtere [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)