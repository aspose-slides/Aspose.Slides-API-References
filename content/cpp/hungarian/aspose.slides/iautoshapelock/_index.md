---
title: IAutoShapeLock
second_title: Aspose.Slides a C++ API referencia
description: Megállapítja, hogy a szülő AutoshapeEx esetében mely műveletek vannak letiltva.
type: docs
weight: 1379
url: /hu/aspose.slides/iautoshapelock/
---
## IAutoShapeLock osztály


Meghatározza, mely műveletek vannak letiltva a szülő AutoshapeEx esetében.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Megállapítja, hogy a beállítási értékek módosítása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Megállapítja, hogy a nyílfejek módosítása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Megállapítja, hogy a forma megtartja-e az oldalarányt átméretezéskor. Olvas **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Megállapítja, hogy a forma körvonalának közvetlen módosítása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Megállapítja, hogy a forma csoportba való hozzáadása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Igazt ad vissza, ha minden zárolási jelző ki van kapcsolva. Csak olvasható **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Megállapítja, hogy a forma mozgatása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Megállapítja, hogy a forma forgatási szögének módosítása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Megállapítja, hogy a forma kiválasztása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Megállapítja, hogy a forma típusának módosítása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Megállapítja, hogy a forma átméretezése tiltott-e. Olvas **bool**. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | Megállapítja, hogy a szöveg szerkesztése tiltott-e. Olvas **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívható közvetlenül vagy a [LockContext](../../system/lockcontext/) őrzőobjektummal. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referencián keresztül. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referencián keresztül. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként összehasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Megállapítja, hogy a beállítási értékek módosítása tiltott-e. Ír **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Megállapítja, hogy a nyílfejek módosítása tiltott-e. Ír **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Megállapítja, hogy a forma megtartja-e az oldalarányt átméretezéskor. Ír **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Megállapítja, hogy a forma körvonalának közvetlen módosítása tiltott-e. Ír **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Megállapítja, hogy a forma csoportba való hozzáadása tiltott-e. Ír **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Megállapítja, hogy a forma mozgatása tiltott-e. Ír **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Megállapítja, hogy a forma forgatási szögének módosítása tiltott-e. Ír **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Megállapítja, hogy a forma kiválasztása tiltott-e. Ír **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Megállapítja, hogy a forma típusának módosítása tiltott-e. Ír **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Megállapítja, hogy a forma átméretezése tiltott-e. Ír **bool**. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | Megállapítja, hogy a szöveg szerkesztése tiltott-e. Ír **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra történő átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívható közvetlenül vagy a [LockContext](../../system/lockcontext/) őrzőobjektummal. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon intelligens mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IBaseShapeLock](../ibaseshapelock/)
* Névterület [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)