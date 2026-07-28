---
title: IListImplValueType
second_title: Aspose.Slides C++ API Referencia
description: "Stubb, amely a System::Collections::IList interfészt valósítja meg a System::Collections::Generic::List objektumon, értéktípusokhoz készült implementáció."
type: docs
weight: 144
url: /hu/system.collections/ilistimplvaluetype/
---
## IListImplValueType osztály

Stub, amely megvalósítja a [System::Collections::IList](../ilist/) interfészt a [System::Collections::Generic::List](../../system.collections.generic/list/) objektumon; implementáció érték típusok számára.

```cpp
template<typename T>class IListImplValueType : public virtual System::Collections::IList
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| int [Add](./add/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Az elemet a lista végéhez adja hozzá. |
| void [Clear](./clear/)() override | Törli az összes elemet. |
| **bool** [Contains](./contains/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) const override | Ellenőrzi, hogy az elem jelen van-e a listában. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Az objektumokat a C# [Object.Equals](../../system/object/equals/) szintaxis szerint hasonlítja össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referencia típusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Hasonítja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Hasonítja a C#-stílusú lebegőpontos összehasonlítást, ahol két NaN-t egyenlőnek tekint, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| int [get_Count](./get_count/)() const override | [ICollection.get_Count()](../icollection/get_count/) metódus implementációja: a gyűjteményben lévő elemek számát adja vissza. |
| virtual **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() const | Visszaadja azt az értéket, amely jelzi, hogy a listának rögzített mérete van-e. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Visszaadja az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::IEnumerator](../ienumerator/)\> [GetEnumerator](./getenumerator/)() override | [IEnumerable.GetEnumerator()](../ienumerable/getenumerator/) implementációja: visszaad egy enumerátort, amely végigiterál egy gyűjteményen. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógja. Lehetővé teszi egyedi objektumok hashelését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Visszaadja az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógja. |
| [SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)(int, int) const override | Visszaadja a megadott indexnél lévő elemet. |
|  [IListImplValueType](./ilistimplvaluetype/)([System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<T\>\>) | Új objektumpéldányt hoz létre. |
| int [IndexOf](./indexof/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) const override | Visszaadja az elem tárolóban való első megjelenésének indexét. |
| void [Insert](./insert/)(int, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Az elemet a megadott pozícióba illeszti, eltolva a többi elemet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógja. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógja. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Objektumot hoz létre. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadó operátor. Valójában semmit nem másol, csak új objektumot inicializál, és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Az objektumokat referenciával hasonlítja össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciaként hasonlítja össze az értéktípusú objektumot a nullptr-val. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| void [Remove](./remove/)([SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Eltávolítja a megadott elem első előfordulását a listából. |
| void [RemoveAt](./removeat/)(int) override | Eltávolítja az elemet a megadott pozícióban. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja a n'th sablonargumentumot gyenge mutatóra (ahelyett, hogy megosztott lenne). Lehetővé teszi a mutatók konténerben történő átváltását gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Visszaadja a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógja. Lehetővé teszi egyedi objektumok stringgé alakítását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrzőobjektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [IList](../ilist/)
* Névtere [System::Collections](../)
* Könyvtár [Aspose.Slides](../../)