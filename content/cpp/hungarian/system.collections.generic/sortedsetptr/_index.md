---
title: SortedSetPtr
second_title: Aspose.Slides C++ API hivatkozás
description: Pointer a SortedSet hivatkozások tárolásához. Ez a típus egy pointer, amely más objektumok törlését kezeli. Stack-en kell lefoglalni, és függvényeknek érték szerint vagy const referenciaként kell átadni.
type: docs
weight: 586
url: /hu/system.collections.generic/sortedsetptr/
---
## SortedSetPtr osztály

Pointer to keep [SortedSet](../sortedset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class SortedSetPtr : public System::SmartPtr<SortedSet<T>>
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | [begin()](../../system/smartptr/begin/) metódushoz tartozó accessor egy alapsorozat gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely rendelkezik [begin()](../../system/smartptr/begin/) metódussal. |
| auto [begin](../../system/smartptr/begin/)() const | [begin()](../../system/smartptr/begin/) metódushoz tartozó accessor egy alapsorozat gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely rendelkezik [begin()](../../system/smartptr/begin/) metódussal. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a pointert saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a pointert az ős típusra static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a pointert a származtatott típusra dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a pointert a származtatott típusra dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | [cbegin()](../../system/smartptr/cbegin/) metódushoz tartozó accessor egy alapsorozat gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely rendelkezik [cbegin()](../../system/smartptr/cbegin/) metódussal. |
| auto [cend](../../system/smartptr/cend/)() const | [cend()](../../system/smartptr/cend/) metódushoz tartozó accessor egy alapsorozat gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely rendelkezik [cend()](../../system/smartptr/cend/) metódussal. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átkonvertálja a pointert másik típusra a const_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a pointert másik típusra a dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | [end()](../../system/smartptr/end/) metódushoz tartozó accessor egy alapsorozat gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely rendelkezik [end()](../../system/smartptr/end/) metódussal. |
| auto [end](../../system/smartptr/end/)() const | [end()](../../system/smartptr/end/) metódushoz tartozó accessor egy alapsorozat gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely rendelkezik [end()](../../system/smartptr/end/) metódussal. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | A mutatott objektumot adja vissza. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | A pointer módját adja vissza. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | A mutatott objektumot adja vissza, de ellenőrzi, hogy a pointer megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | A hivatkozott objektumra mutató megosztott pointerek számát adja vissza, beleértve a jelenlegit is. Ellenőrzi, hogy a jelenlegi pointer megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | A jelenleg hivatkozott objektumot adja vissza (ha van), különben kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | A mutatott objektumot adja vissza (ha van) vagy nullptr. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | A hivatkozott objektumot adja vissza. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | A mutatott objektumot adja vissza (ha van) vagy nullptr. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum egy adott típusú vagy annak leszármazottja-e. A C# 'is' szintaxisát követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a pointer egy másik, a tulajdonosa által nem birtokolt objektumra mutat-e (aliasing konstruktortól származik). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a pointer megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a pointer gyenge (weak) módban van-e. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a pointer nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a pointer null-e. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | A mutatott objektumra mutató referenciát adja vissza. Ellenőrzi, hogy a pointer nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítást biztosít a [SmartPtr](../../system/smartptr/) osztály számára. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítást biztosít a [SmartPtr](../../system/smartptr/) osztály számára. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Az [SmartPtr](../../system/smartptr/) objektumot move-assignálja. x használhatatlanná válik. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | A [SmartPtr](../../system/smartptr/) objektumot copy-assignálja. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | A [SmartPtr](../../system/smartptr/) objektumot copy-assignálja. Végrehajtja a szükséges típuskonverziókat. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | A nyers pointert a [SmartPtr](../../system/smartptr/) objektumhoz rendeli. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | A pointer értékét nullptr-ra állítja. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a pointer nullptr-re mutat-e. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasing-et (aliasing konstruktor által létrehozott) a pointerről, és biztosítja, hogy ugyanazt az objektumot menedzselje (ha megosztott) vagy kövesse (ha gyenge) amelyre mutat. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A pointert nullptr-re állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a pointer módját. Megváltoztathatja a hivatkozott objektum referenciáit. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a szükséges módú [SmartPtr](../../system/smartptr/) objektumot. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a szükséges módú null-pointer [SmartPtr](../../system/smartptr/) objektumot. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a [SmartPtr](../../system/smartptr/) objektumot, amely a megadott objektumra mutat, vagy átalakítja a nyers pointert [SmartPtr](../../system/smartptr/)-ra. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukcióval hozza létre a [SmartPtr](../../system/smartptr/) objektumot. Mindkét pointer ugyanarra az objektumra mutat a létrehozás után. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukcióval hozza létre a [SmartPtr](../../system/smartptr/) objektumot. Mindkét pointer ugyanarra az objektumra mutat a létrehozás után. Ha engedélyezett, típuskonverziót hajt végre. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move konstrukcióval hozza létre a [SmartPtr](../../system/smartptr/) objektumot. Gyakorlatban két pointert cserél, ha mindkettő ugyanabban a módban van. x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átalakítja a hivatkozott tömb típusát egy új, különböző típusú tömb létrehozásával. Hasznos, ha C#-ban van egy tömb típus konverzió, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstrukció lefordításához használják. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely megosztja a tulajdonosi információkat a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt pointer p-t tartalmaz. |
|  [SortedSetPtr](./sortedsetptr/)() | Null pointer konstruktor. |
|  [SortedSetPtr](./sortedsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedSet](../sortedset/)\<T\>\>\&) | Másoló konstruktor. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átkonvertálja a pointert másik típusra a static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Bármely pointer típust átalakít [Object](../../system/object/) pointerre. Nem igényli a Pointee_ típus teljes definiálását. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövidítés a [System::TypeInfo](../../system/typeinfo/) objektum lekéréséhez a Pointee_ típus számára. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Ha szükséges, csökkenti a mutatott objektum referenciáit és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névtere [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)