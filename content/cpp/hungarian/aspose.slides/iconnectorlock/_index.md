---
title: IConnectorLock
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogy a szülő Connectoron mely műveletek vannak letiltva.
type: docs
weight: 1860
url: /hu/aspose.slides/iconnectorlock/
---
## IConnectorLock osztály


Meghatározza, hogy mely műveletek vannak letiltva a szülő [Connector](../connector/)-on.

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metódusok

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusu objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Meghatározza, hogy az állítási értékek megváltoztatása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Meghatározza, hogy a nyilak megváltoztatása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Meghatározza, hogy az alakzatnak meg kell-e őriznie az arányt átméretezéskor. Olvas **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Meghatározza, hogy az alakzat körvonalának közvetlen megváltoztatása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Meghatározza, hogy az alakzat csoportba való hozzáadása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Igaz értéket ad vissza, ha minden zárzási jelző le van tiltva. Csak olvasható **bool**. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | Meghatározza, hogy az alakzat mozgatása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Meghatározza, hogy az alakzat forgatási szögének megváltoztatása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Meghatározza, hogy az alakzat kiválasztása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Meghatározza, hogy az alakzat típusának megváltoztatása tiltott-e. Olvas **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Meghatározza, hogy az alakzat átméretezése tiltott-e. Olvas **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példányát képviseli-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) szemelő objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusu objektumot nullptr-el. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Meghatározza, hogy az állítási értékek megváltoztatása tiltott-e. Ír **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Meghatározza, hogy a nyilak megváltoztatása tiltott-e. Ír **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Meghatározza, hogy az alakzatnak meg kell-e őriznie az arányt átméretezéskor. Ír **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Meghatározza, hogy az alakzat körvonalának közvetlen megváltoztatása tiltott-e. Ír **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Meghatározza, hogy az alakzat csoportba való hozzáadása tiltott-e. Ír **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | Meghatározza, hogy az alakzat mozgatása tiltott-e. Ír **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Meghatározza, hogy az alakzat forgatási szögének megváltoztatása tiltott-e. Ír **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Meghatározza, hogy az alakzat kiválasztása tiltott-e. Ír **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Meghatározza, hogy az alakzat típusának megváltoztatása tiltott-e. Ír **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Meghatározza, hogy az alakzat átméretezése tiltott-e. Ír **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (nem megosztottként). Lehetővé teszi a mutatók konténerekben való gyenge módra való átváltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; ehelyett használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; ehelyett használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) szemelő objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; ehelyett használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; ehelyett használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IBaseShapeLock](../ibaseshapelock/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)