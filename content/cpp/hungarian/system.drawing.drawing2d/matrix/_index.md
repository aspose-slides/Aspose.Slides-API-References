---
title: Matrix
second_title: Aspose.Slides C++ API-referencia
description: "3x3-as mátrixot reprezentál, amely transzformációs műveleteket definiál. Ennek az osztálynak az objektumait csak a System::MakeObject() függvénnyel szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stack-en vagy az operator new használatával, mivel ez futási hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót, hogy argumentumként átadja a függvényeknek."
type: docs
weight: 118
url: /hu/system.drawing.drawing2d/matrix/
---
## Matrix osztály

Represents a 3x3 matrix that defines transform operations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Matrix : public System::Object
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\> [Clone](./clone/)() const | Létrehozza az aktuális objektum másolatát. |
| void [Dispose](./dispose/)() | Felszabadítja az aktuális objektum által megszerzett összes operációs rendszer erőforrást. |
| **bool** [Equals](./equals/)([ptr](../../system/object/ptr/)) override | Megvizsgálja, hogy a megadott objektum [Matrix](./) és azonos-e az aktuális objektummal. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, annak ellenére, hogy az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_Elements](./get_elements/)() const | Visszaad egy tömböt, amely a mátrix elemeit a következő sorrendben tartalmazza: m11, m12, m21, m22, dx, dy. |
| **bool** [get_IsIdentity](./get_isidentity/)() const | Megállapítja, hogy az aktuális objektum által reprezentált mátrix egységmátrix-e. |
| **bool** [get_IsInvertible](./get_isinvertible/)() const | Megállapítja, hogy az aktuális objektum által reprezentált mátrix invertálható-e. |
| **float** [get_OffsetX](./get_offsetx/)() const | Visszaadja a jelenlegi objektum által reprezentált mátrix X transzlációs értékét. |
| **float** [get_OffsetY](./get_offsety/)() const | Visszaadja a jelenlegi objektum által reprezentált mátrix Y transzlációs értékét. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi a saját objektumok hash-olását. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| void [Invert](./invert/)() | Inverzálja az aktuális objektum által reprezentált mátrixot. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
|  [Matrix](./matrix/)() | Létrehoz egy új példányt a [Matrix](./) osztályból, ami egy egységmátrixot reprezentál. |
|  [Matrix](./matrix/)(**float**, **float**, **float**, **float**, **float**, **float**) | Létrehoz egy új példányt a [Matrix](./) osztályból, és a megadott értékekkel inicializálja. |
|  [Matrix](./matrix/)(const [Rectangle](../../system.drawing/rectangle/)\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Létrehoz egy új példányt a [Matrix](./) osztályból a megadott téglalap és pontok tömbje által definiált geometriai transzformációhoz. |
|  [Matrix](./matrix/)(const [RectangleF](../../system.drawing/rectanglef/)\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Létrehoz egy új példányt a [Matrix](./) osztályból a megadott téglalap és pontok tömbje által definiált geometriai transzformációhoz. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&) | Az aktuális objektum által reprezentált mátrixot megszorozza a megadott mátrixszal. |
| void [Multiply](./multiply/)(const [SharedPtr](../../system/sharedptr/)\<[Matrix](./)\>\&, [MatrixOrder](../matrixorder/)) | Az aktuális objektum által reprezentált mátrixot megszorozza a megadott mátrixszal. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában semmit nem másol, csak egy új objektumot inicializál és lehetővé teszi az alosztályok másoló konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referencián. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referencián. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával összehasonlítja az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) speciális változata stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [Reset](./reset/)() | Visszaállítja az aktuális objektum által reprezentált mátrixot, hogy az egységmátrix legyen. |
| void [Rotate](./rotate/)(**float**) | Az aktuális objektum által reprezentált mátrixot az óramutató járásával megegyező irányban forgatja a megadott szöggel. |
| void [Rotate](./rotate/)(**float**, [MatrixOrder](../matrixorder/)) | Az aktuális objektum által reprezentált mátrixot az óramutató járásával megegyező irányban az origó körül forgatja a megadott szöggel. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&) | Az aktuális objektum által reprezentált mátrixot az óramutató járásával megegyező irányban a megadott pont körül forgatja a megadott szöggel. |
| void [RotateAt](./rotateat/)(**float**, const [PointF](../../system.drawing/pointf/)\&, [MatrixOrder](../matrixorder/)) | Az aktuális objektum által reprezentált mátrixot az óramutató járásával megegyező irányban a megadott pont körül forgatja a megadott szöggel. |
| void [Scale](./scale/)(**float**, **float**) | Alkalmazza a megadott skálavektort az aktuális objektum által reprezentált mátrixra. |
| void [Scale](./scale/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Alkalmazza a megadott skálavektort az aktuális objektum által reprezentált mátrixra. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi, hogy a tárolók mutatóit gyenge módra állítsa. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [Shear](./shear/)(**float**, **float**) | Alkalmazza a megadott nyíróvektort az aktuális objektum által reprezentált mátrixra. |
| void [Shear](./shear/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Alkalmazza a megadott nyíróvektort az aktuális objektum által reprezentált mátrixra. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi az egyedi objektumok stringgé konvertálását. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Alkalmazza az aktuális objektum által reprezentált mátrix által meghatározott geometriai transzformációt a megadott pontokra. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Alkalmazza az aktuális objektum által reprezentált mátrix által meghatározott geometriai transzformációt a megadott pontokra. |
| void [TransformPoints](./transformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Alkalmazza az aktuális objektum által reprezentált mátrix által meghatározott geometriai transzformációt a megadott pontokra. |
| void [TransformPoints](./transformpoints/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Alkalmazza az aktuális objektum által reprezentált mátrix által meghatározott geometriai transzformációt a megadott pontokra. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Csak a méretezési és forgatási komponenseket alkalmazza az aktuális objektum által reprezentált mátrixból a megadott pontokra. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Csak a méretezési és forgatási komponenseket alkalmazza az aktuális objektum által reprezentált mátrixból a megadott pontokra. |
| void [TransformVectors](./transformvectors/)(const [ArrayPtr](../../system/arrayptr/)\<[PointF](../../system.drawing/pointf/)\>\&) | Csak a méretezési és forgatási komponenseket alkalmazza az aktuális objektum által reprezentált mátrixból a megadott pontokra. |
| void [TransformVectors](./transformvectors/)(const System::Details::ArrayView\<[PointF](../../system.drawing/pointf/)\>\&) | Csak a méretezési és forgatási komponenseket alkalmazza az aktuális objektum által reprezentált mátrixból a megadott pontokra. |
| void [Translate](./translate/)(**float**, **float**) | Alkalmazza a megadott transzformációs vektort az aktuális objektum által reprezentált mátrixra. |
| void [Translate](./translate/)(**float**, **float**, [MatrixOrder](../matrixorder/)) | Alkalmazza a megadott transzformációs vektort az aktuális objektum által reprezentált mátrixra. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| void [VectorTransformPoints](./vectortransformpoints/)(const [ArrayPtr](../../system/arrayptr/)\<[Point](../../system.drawing/point/)\>\&) | Minden vektort egy tömbben megszorozza az aktuális objektum által reprezentált mátrixszal. |
| void [VectorTransformPoints](./vectortransformpoints/)(const System::Details::ArrayView\<[Point](../../system.drawing/point/)\>\&) | Minden vektort egy tömbben megszorozza az aktuális objektum által reprezentált mátrixszal. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Matrix](./~matrix/)() | Dekonstruktor. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Drawing::Drawing2D](../)
* Könyvtár [Aspose.Slides](../../)