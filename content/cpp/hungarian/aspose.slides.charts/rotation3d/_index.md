---
title: Rotation3D
second_title: Aspose.Slides C++ API referencia
description: Ábrázolja egy diagram 3D forgatását.
type: docs
weight: 1327
url: /hu/aspose.slides.charts/rotation3d/
---
## Rotation3D osztály

A diagram 3D forgatásának ábrázolása.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantikájával. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | Visszaadja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). Olvassa **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | Megadja egy 3D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). Olvassa **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | Visszaadja a perspektíva értékét (látómező szöge) 3D diagramokhoz (0 és 240 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke igaz. Olvassa **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | Megállapítja, hogy a diagram tengelyei derékszögek-e, a perspektíva helyett. Más szóval meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgatásától vagy emelkedésétől. Olvassa **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | Visszaadja az X tengely körüli forgatás fokát, azaz a Y irányban 3D diagramoknál (-90 és 90 fok között). A tulajdonság egyezik az ECMA-376 21.2.2.157 rotX (X Rotation) elemével és a PowerPoint 2007+ "Y Rotation" beállításával. Olvassa **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | Visszaadja az Y tengely körüli forgatás fokát, azaz az X irányban 3D diagramoknál (0 és 360 fok között). A tulajdonság egyezik az ECMA-376 21.2.2.158 rotY (Y Rotation) elemével és a PowerPoint 2007+ "X Rotation" beállításával. Olvassa **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz tartozó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a cél típusa által leírt példány-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referencia alapján hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia alapján hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | Beállítja egy 3D diagram mélységét a diagram szélességének százalékában (20 és 2000 százalék között). Írja **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | Megadja egy 3D diagram magasságát a diagram szélességének százalékában (5 és 500 százalék között). Írja **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | Beállítja a perspektíva értékét (látómező szög) 3D diagramokhoz (0 és 240 között). Figyelmen kívül marad, ha a RightAngleAxes tulajdonság értéke igaz. Írja **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | Megállapítja, hogy a diagram tengelyei derékszögek-e, a perspektíva helyett. Más szóval meghatározza, hogy a diagram tengelyeinek szögei függetlenek-e a diagram forgatásától vagy emelkedésétől. Írja **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | Beállítja az X tengely körüli forgatás fokát, azaz a Y irányban 3D diagramoknál (-90 és 90 fok között). A tulajdonság egyezik az ECMA-376 21.2.2.157 rotX (X Rotation) elemével és a PowerPoint 2007+ "Y Rotation" beállításával. Írja **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | Beállítja az Y tengely körüli forgatás fokát, azaz az X irányban 3D diagramoknál (0 és 360 fok között). A tulajdonság egyezik az ECMA-376 21.2.2.158 rotY (Y Rotation) elemével és a PowerPoint 2007+ "X Rotation" beállításával. Írja **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerekben történő gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok karakterlánccá konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IRotation3D](../irotation3d/)
* Osztály [IDOMObject](../../aspose.slides/idomobject/)
* Névtere [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)