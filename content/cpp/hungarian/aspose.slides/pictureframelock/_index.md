---
title: PictureFrameLock
second_title: Aspose.Slides C++ API referencia
description: Meghatározza, hogy a szülő PictureFrame-en mely műveletek vannak letiltva.
type: docs
weight: 4746
url: /hu/aspose.slides/pictureframelock/
---
## PictureFrameLock osztály

Meghatározza, hogy mely műveletek vannak letiltva a(z) [PictureFrame](../pictureframe/) szülőn.

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objketumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika használatával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Meghatározza, hogy a beállítási értékek módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Meghatározza, hogy a nyílfejek módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Meghatározza, hogy az alakzatnak meg kell-e őriznie az oldalarányt átméretezéskor. Olvas **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Meghatározza, hogy a képvágás tiltott-e. Olvas **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Meghatározza, hogy ennek az alakzatnak a kontúrjának közvetlen módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Meghatározza, hogy az alakzat csoportba helyezése tiltott-e. Olvas **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Igaz értékkel tér vissza, ha az összes zárolási jelző le van tiltva. Csak olvasható **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Meghatározza, hogy az alakzat mozgatása tiltott-e. Olvas **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Meghatározza, hogy az alakzat forgatási szögének módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Meghatározza, hogy az alakzat kiválasztása tiltott-e. Olvas **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Meghatározza, hogy az alakzat típusának módosítása tiltott-e. Olvas **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Meghatározza, hogy az alakzat átméretezése tiltott-e. Olvas **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum példány-e a targetType által leírt típusból. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja az értéktípusú objektumot a nullptr-hoz. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Meghatározza, hogy a beállítási értékek módosítása tiltott-e. Ír **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Meghatározza, hogy a nyílfejek módosítása tiltott-e. Ír **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Meghatározza, hogy az alakzatnak meg kell-e őriznie az oldalarányt átméretezéskor. Ír **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Meghatározza, hogy a képvágás tiltott-e. Ír **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Meghatározza, hogy ennek az alakzatnak a kontúrjának közvetlen módosítása tiltott-e. Ír **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Meghatározza, hogy az alakzat csoportba helyezése tiltott-e. Ír **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Meghatározza, hogy az alakzat mozgatása tiltott-e. Ír **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Meghatározza, hogy az alakzat forgatási szögének módosítása tiltott-e. Ír **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Meghatározza, hogy az alakzat kiválasztása tiltott-e. Ír **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Meghatározza, hogy az alakzat típusának módosítása tiltott-e. Ír **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Meghatározza, hogy az alakzat átméretezése tiltott-e. Ír **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóvá állítja (a megosztott helyett). Lehetővé teszi a mutatók átkapcsolását a gyenge módra a konténerben. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [BaseShapeLock](../baseshapelock/)
* Osztály [IPictureFrameLock](../ipictureframelock/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)