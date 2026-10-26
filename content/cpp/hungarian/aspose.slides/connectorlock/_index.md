---
title: ConnectorLock
second_title: Aspose.Slides for C++ API referencia
description: Meghatározza, hogy a szülő Connectoron mely műveletek vannak letiltva.
type: docs
weight: 495
url: /hu/aspose.slides/connectorlock/
---
## ConnectorLock osztály

Meghatározza, hogy mely műveletek vannak letiltva a szülő [Connector](../connector/)-ben.

```cpp
class ConnectorLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IConnectorLock
```

## Módszerek

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objketumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értéknek, köztük a NaN-nek sem egyenlő. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN semelyik értéknek, köztük a NaN-nek sem egyenlő. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Meghatározza, hogy a beállítási értékek módosítása tiltott-e. Read **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Meghatározza, hogy a nyílhegyek módosítása tiltott-e. Read **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Meghatározza, hogy a forma méretezéskor megőrizze-e az oldalarányt. Read **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Meghatározza, hogy a forma körvonalának közvetlen módosítása tiltott-e. Read **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Meghatározza, hogy a forma csoportba való hozzáadása tiltott-e. Read **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Igazat ad, ha minden lock-flag le van tiltva. Read-only **bool**. |
| **bool** [get_PositionMove](./get_positionmove/)() override | Meghatározza, hogy a forma mozgatása tiltott-e. Read **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Meghatározza, hogy a forma forgásszögének módosítása tiltott-e. Read **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Meghatározza, hogy a forma kiválasztása tiltott-e. Read **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Meghatározza, hogy a forma típusának módosítása tiltott-e. Read **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Meghatározza, hogy a forma átméretezése tiltott-e. Read **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal kapcsolatos referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hasítását. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak inicializálja az új objektumot, és lehetővé teszi az alosztályok másolási konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat hivatkozással hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat hivatkozással hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-alapú összehasonlítás értéktípusú objektum és nullptr között. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Meghatározza, hogy a beállítási értékek módosítása tiltott-e. Write **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Meghatározza, hogy a nyílhegyek módosítása tiltott-e. Write **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Meghatározza, hogy a forma méretezéskor megőrizze-e az oldalarányt. Write **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Meghatározza, hogy a forma körvonalának közvetlen módosítása tiltott-e. Write **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Meghatározza, hogy a forma csoportba való hozzáadása tiltott-e. Write **bool**. |
| void [set_PositionMove](./set_positionmove/)(**bool**) override | Meghatározza, hogy a forma mozgatása tiltott-e. Write **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Meghatározza, hogy a forma forgásszögének módosítása tiltott-e. Write **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Meghatározza, hogy a forma kiválasztása tiltott-e. Write **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Meghatározza, hogy a forma típusának módosítása tiltott-e. Write **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Meghatározza, hogy a forma átméretezése tiltott-e. Write **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóként (a megosztott helyett). Lehetővé teszi a mutatók konténerekben való gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [BaseShapeLock](../baseshapelock/)
* Osztály [IConnectorLock](../iconnectorlock/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)