---
title: StringBuilder
second_title: Aspose.Slides C++ API referenciája
description: "Puffer a karakterlánc részletekben történő összegyűjtéséhez. Ez a típus akár a stack-en értéktípusként, akár a heap-en a System::MakeObject() függvény használatával helyezhető el. Az objektum elhelyezése után soha ne keverje össze ezt a két felhasználási esetet: a SmartPtr mutatók stack-en elhelyezett objektumokra való használata szigorúan tilos."
type: docs
weight: 326
url: /hu/system.text/stringbuilder/
---
## StringBuilder osztály

[Buffer](../../system/buffer/) a karakterlánc részeinek részletekben történő összegyűjtésére. Ez a típus vagy a stack-en érték típusként, vagy a heap-en a [System::MakeObject()](../../system/makeobject/) függvény használatával helyezhető el. Az objektum elhelyezése után soha ne keverje össze ezt a két felhasználási esetet: a [SmartPtr](../../system/smartptr/) mutatók stack-en elhelyezett objektumokra való használata szigorúan tilos.

```cpp
class StringBuilder : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Karaktert ad a builderhez. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Karaktereket ad a builderhez. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Karaktertömböt ad a builderhez. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Karaktertömb szeletet ad a builderhez. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Karakterláncot ad a builderhez. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Karakterlánc szeletet ad a builderhez. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Objektum karakterlánc ábrázolását adja a builderhez. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | A builder tartalmát adja a builderhez. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Lebegőpontos értéket ad a builderhez. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Lebegőpontos értéket ad a builderhez. |
| [StringBuilder](./) * [Append](./append/)(int) | Egész szám értéket ad a builderhez. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Aritmetikus értéket ad a builderhez. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Az enum érték karakterlánc ábrázolását adja a builderhez. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Formázott karakterláncot fűz hozzá a builderhez. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Formázott karakterláncot fűz hozzá a builderhez. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Új sor karaktert fűz hozzá a builderhez. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Karakterláncot fűz hozzá, majd újsor karaktert a builderhez. |
| [StringBuilder](./) * [Clear](./clear/)() | Az összes karaktert eltávolítja a builderből. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | A builder adatait meglévő tömbpozíciókba másolja. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Biztosítja, hogy a [System.Text.StringBuilder](./) ezen példányának kapacitása legalább a megadott érték legyen. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, bár az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| int [get_Capacity](./get_capacity/)() const | Az aktuális kapacitást adja a string buildernek. |
| int [get_Length](./get_length/)() const | Az aktuálisan a builderben lévő karakterlánc hosszát adja vissza. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Az objektumhoz társított referencia számláló adatstruktúrát adja vissza. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Engedélyezi az egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Az objektum tényleges típusát adja vissza. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| char_t [idx_get](./idx_get/)(int) const | A megadott pozícióban lévő karaktert adja vissza. |
| void [idx_set](./idx_set/)(int, char_t) | Beállítja a karaktert a megadott pozíción. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Karakterláncot szúr be a builder rögzített pozíciójába. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Ismételt karakterláncot szúr be a builder rögzített pozíciójába. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Karaktert szúr be a builder rögzített pozíciójába. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Karaktereket szúr be a builder rögzített pozíciójába. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Értéket szúr be a builder rögzített pozíciójába. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Implementálja a C# lock() utasítást zárolásként. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi az egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| char_t [operator[]](./operator[]/)(int) const | A megadott pozícióban lévő karaktert adja vissza. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referencia szerint hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia szerint hasonlítja az értéktípusú objektumot a nullptr-hez. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Egy szakaszt eltávolít a builderből. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Az alkövet helyettesíti a builderben. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | A builder tartományában helyettesíti az alkövet. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | A builderben helyettesíti a karaktert. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | A builder tartományában helyettesíti a karaktert. |
| void [set_Capacity](./set_capacity/)(int) | Beállítja a string builder aktuális kapacitását. |
| void [set_Length](./set_length/)(int) | Metszi vagy kiterjeszti a string buildert a megadott hosszra. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a shared helyett). Lehetővé teszi a tárolókban lévő mutatók weak módba váltását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Az aktuális értéket adja vissza a megosztott referencia számlálónak. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
|  [StringBuilder](./stringbuilder/)() | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(int) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Konstruktor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Konstruktor. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Az aktuálisan a builderben lévő karakterláncot adja vissza. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Az aktuálisan a builderben lévő részkarakterláncot adja vissza. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementálja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Implementálja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentinel objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |
|  [~StringBuilder](./~stringbuilder/)() | Destruktor. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtér [System::Text](../)
* Könyvtár [Aspose.Slides](../../)