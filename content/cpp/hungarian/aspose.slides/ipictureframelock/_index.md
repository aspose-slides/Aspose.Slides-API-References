---
title: IPictureFrameLock
second_title: Aspose.Slides C++ API referenciája
description: Meghatározza, hogy a szülő PictureFrameEx-en mely műveletek vannak letiltva.
type: docs
weight: 3264
url: /hu/aspose.slides/ipictureframelock/
---
## IPictureFrameLock osztály

Meghatározza, hogy mely műveletek vannak letiltva a szülő PictureFrameEx-en.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | A C# [Object.Equals](../../system/object/equals/) szemantika használatával hasonlítja össze az objektumokat. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Megállapítja, hogy a beállítási értékek módosítása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Megállapítja, hogy a nyílhegyek módosítása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Megállapítja, hogy a forma megőrizze-e az arányt átméretezéskor. Olvasás **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | Megállapítja, hogy a kép vágása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Megállapítja, hogy a forma körvonalának közvetlen módosítása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Megállapítja, hogy a forma csoportba való hozzáadása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Igaz értéket ad vissza, ha minden zárolási jelző le van tiltva. Csak olvasható **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Megállapítja, hogy a forma mozgatása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Megállapítja, hogy a forma forgatásának szöge módosítása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Megállapítja, hogy a forma kiválasztása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Megállapítja, hogy a forma típusának módosítása tiltott-e. Olvasás **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Megállapítja, hogy a forma átméretezése tiltott-e. Olvasás **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak egy új objektumot inicializál, és lehetővé teszi az alosztályok másolásos konstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítás értéktípusú objektummal és nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja a string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciák számát a megadott értékkel. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Megállapítja, hogy a beállítási értékek módosítása tiltott-e. Írás **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Megállapítja, hogy a nyílhegyek módosítása tiltott-e. Írás **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Megállapítja, hogy a forma megőrizze-e az arányt átméretezéskor. Írás **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | Megállapítja, hogy a kép vágása tiltott-e. Írás **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Megállapítja, hogy a forma körvonalának közvetlen módosítása tiltott-e. Írás **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Megállapítja, hogy a forma csoportba való hozzáadása tiltott-e. Írás **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Megállapítja, hogy a forma mozgatása tiltott-e. Írás **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Megállapítja, hogy a forma forgatásának szöge módosítása tiltott-e. Írás **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Megállapítja, hogy a forma kiválasztása tiltott-e. Írás **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Megállapítja, hogy a forma típusának módosítása tiltott-e. Írás **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Megállapítja, hogy a forma átméretezése tiltott-e. Írás **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóra (nem megosztott) állítja. Lehetővé teszi a mutatók átkapcsolását a tárolókban gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciák számát. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciák számát. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciák számát. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciák számát. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
## Lásd még

* Osztály [IBaseShapeLock](../ibaseshapelock/)
* Névtér [Aspose::Slides](../)
* Könyvtár [Aspose.Slides](../../)