---
title: ColorMatrix
second_title: Aspose.Slides for C++ API referencia
description: "Egy 5x5-ös mátrixot reprezentál, amely az RGBAW színtér koordinátáit tartalmazza. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény segítségével szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót a függvények argumentumaként való átadásra."
type: docs
weight: 27
url: /hu/system.drawing.imaging/colormatrix/
---
## ColorMatrix osztály

Representál egy 5x5-ös mátrixot, amely az RGBAW színtér koordinátáit tartalmazza. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../../system/makeobject/) függvény segítségével szabad lefoglalni. Soha ne hozza létre ennek a típusnak a példányt a stacken vagy az new operátorral, mivel ez futásidejű hibákat és/vagy állítási hibákat okozhat. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../../system/smartptr/) mutatóba, és használja ezt a mutatót a függvények argumentumaként.

```cpp
class ColorMatrix : public System::Object
```

## Metódusok

| Method | Description |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Létrehoz egy új példányt a [ColorMatrix](./) osztályból, és az identitásmátrix értékeivel inicializálja. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Létrehoz egy új példányt a [ColorMatrix](./) osztályból, és a megadott értékekkel inicializálja. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| **float** [get_Matrix00](./get_matrix00/)() const | Visszaad egy értéket a 0. sorban és a 0. oszlopban. |
| **float** [get_Matrix01](./get_matrix01/)() const | Visszaad egy értéket a 0. sorban és a 1. oszlopban. |
| **float** [get_Matrix02](./get_matrix02/)() const | Visszaad egy értéket a 0. sorban és a 2. oszlopban. |
| **float** [get_Matrix03](./get_matrix03/)() const | Visszaad egy értéket a 0. sorban és a 3. oszlopban. |
| **float** [get_Matrix04](./get_matrix04/)() const | Visszaad egy értéket a 0. sorban és a 4. oszlopban. |
| **float** [get_Matrix10](./get_matrix10/)() const | Visszaad egy értéket a 1. sorban és a 0. oszlopban. |
| **float** [get_Matrix11](./get_matrix11/)() const | Visszaad egy értéket a 1. sorban és a 1. oszlopban. |
| **float** [get_Matrix12](./get_matrix12/)() const | Visszaad egy értéket a 1. sorban és a 2. oszlopban. |
| **float** [get_Matrix13](./get_matrix13/)() const | Visszaad egy értéket a 1. sorban és a 3. oszlopban. |
| **float** [get_Matrix14](./get_matrix14/)() const | Visszaad egy értéket a 1. sorban és a 4. oszlopban. |
| **float** [get_Matrix20](./get_matrix20/)() const | Visszaad egy értéket a 2. sorban és a 0. oszlopban. |
| **float** [get_Matrix21](./get_matrix21/)() const | Visszaad egy értéket a 2. sorban és a 1. oszlopban. |
| **float** [get_Matrix22](./get_matrix22/)() const | Visszaad egy értéket a 2. sorban és a 2. oszlopban. |
| **float** [get_Matrix23](./get_matrix23/)() const | Visszaad egy értéket a 2. sorban és a 3. oszlopban. |
| **float** [get_Matrix24](./get_matrix24/)() const | Visszaad egy értéket a 2. sorban és a 4. oszlopban. |
| **float** [get_Matrix30](./get_matrix30/)() const | Visszaad egy értéket a 3. sorban és a 0. oszlopban. |
| **float** [get_Matrix31](./get_matrix31/)() const | Visszaad egy értéket a 3. sorban és a 1. oszlopban. |
| **float** [get_Matrix32](./get_matrix32/)() const | Visszaad egy értéket a 3. sorban és a 2. oszlopban. |
| **float** [get_Matrix33](./get_matrix33/)() const | Visszaad egy értéket a 3. sorban és a 3. oszlopban. |
| **float** [get_Matrix34](./get_matrix34/)() const | Visszaad egy értéket a 3. sorban és a 4. oszlopban. |
| **float** [get_Matrix40](./get_matrix40/)() const | Visszaad egy értéket a 4. sorban és a 0. oszlopban. |
| **float** [get_Matrix41](./get_matrix41/)() const | Visszaad egy értéket a 4. sorban és a 1. oszlopban. |
| **float** [get_Matrix42](./get_matrix42/)() const | Visszaad egy értéket a 4. sorban és a 2. oszlopban. |
| **float** [get_Matrix43](./get_matrix43/)() const | Visszaad egy értéket a 4. sorban és a 3. oszlopban. |
| **float** [get_Matrix44](./get_matrix44/)() const | Visszaad egy értéket a 4. sorban és a 4. oszlopban. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Megkapja az objektumhoz kapcsolódó referenciacsökkentő adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Megkapja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| **float** [idx_get](./idx_get/)(int, int) | Visszaad egy értéket a megadott sorban és oszlopban. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Beállítja a megadott értéket a mátrixban megadott helyen. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zárolásként. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstruktorát. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Nem másol semmit, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolási konstruktorát. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Érték típusú objektumot referenciával hasonlít össze nullptr-ral. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciacsökkentőt a megadott értékkel. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Beállít egy értéket a 0. sorban és a 0. oszlopban. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Beállít egy értéket a 0. sorban és a 1. oszlopban. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Beállít egy értéket a 0. sorban és a 2. oszlopban. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Beállít egy értéket a 0. sorban és a 3. oszlopban. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Beállít egy értéket a 0. sorban és a 4. oszlopban. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Beállít egy értéket a 1. sorban és a 0. oszlopban. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Beállít egy értéket a 1. sorban és a 1. oszlopban. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Beállít egy értéket a 1. sorban és a 2. oszlopban. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Beállít egy értéket a 1. sorban és a 3. oszlopban. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Beállít egy értéket a 1. sorban és a 4. oszlopban. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Beállít egy értéket a 2. sorban és a 0. oszlopban. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Beállít egy értéket a 2. sorban és a 1. oszlopban. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Beállít egy értéket a 2. sorban és a 2. oszlopban. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Beállít egy értéket a 2. sorban és a 3. oszlopban. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Beállít egy értéket a 2. sorban és a 4. oszlopban. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Beállít egy értéket a 3. sorban és a 0. oszlopban. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Beállít egy értéket a 3. sorban és a 1. oszlopban. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Beállít egy értéket a 3. sorban és a 2. oszlopban. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Beállít egy értéket a 3. sorban és a 3. oszlopban. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Beállít egy értéket a 3. sorban és a 4. oszlopban. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Beállít egy értéket a 4. sorban és a 0. oszlopban. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Beállít egy értéket a 4. sorban és a 1. oszlopban. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Beállít egy értéket a 4. sorban és a 2. oszlopban. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Beállít egy értéket a 4. sorban és a 3. oszlopban. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Beállít egy értéket a 4. sorban és a 4. oszlopban. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett) állítja. Lehetővé teszi a mutatók konténerekben való gyenge módra váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciacsökkentő aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciacsökkentőt. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciacsökkentőt. Nem szabad közvetlenül hívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [System::Drawing::Imaging](../)
* Könyvtár [Aspose.Slides](../../)