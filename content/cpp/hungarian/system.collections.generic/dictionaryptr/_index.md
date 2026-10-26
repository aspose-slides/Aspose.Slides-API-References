---
title: DictionaryPtr
second_title: Aspose.Slides for C++ API Referencia
description: Dictionary mutató osztály operátor túlterhelésekkel. Ez a típus egy pointer, amely más objektum törlését kezeli. Veremre kell allokálni, és értékkel vagy const referenciával átadni a függvényeknek.
type: docs
weight: 170
url: /hu/system.collections.generic/dictionaryptr/
---
## DictionaryPtr osztály

[Dictionary](../dictionary/) pointer osztály operátor túlterhelésekkel. Ez a típus egy pointer, amely más objektum törlését kezeli. Veremre kell allokálni, és értékkel vagy const referenciával átadni a függvényeknek.

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Kulcs típusa. |
| V | Érték típusa. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Getter a [begin()](../../system/smartptr/begin/) metódushoz egy alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik [begin()](../../system/smartptr/begin/) metódussal. |
| auto [begin](../../system/smartptr/begin/)() const | Getter a [begin()](../../system/smartptr/begin/) metódushoz egy alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik [begin()](../../system/smartptr/begin/) metódussal. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a pointert a saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a pointert az ős típusra a static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a pointert a származtatott típusra a dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a pointert a származtatott típusra a dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Getter a [cbegin()](../../system/smartptr/cbegin/) metódushoz egy alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik [cbegin()](../../system/smartptr/cbegin/) metódussal. |
| auto [cend](../../system/smartptr/cend/)() const | Getter a [cend()](../../system/smartptr/cend/) metódushoz egy alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik [cend()](../../system/smartptr/cend/) metódussal. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átkonvertálja a pointert más típusra a const_cast használatával a mutatott objektumon. |
| [DictionaryPtr](./dictionaryptr/)() | Null pointert inicializál. |
| [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | Átkonvertálja a pointer típusát. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a pointert más típusra a dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Getter a [end()](../../system/smartptr/end/) metódushoz egy alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik [end()](../../system/smartptr/end/) metódussal. |
| auto [end](../../system/smartptr/end/)() const | Getter a [end()](../../system/smartptr/end/) metódushoz egy alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik [end()](../../system/smartptr/end/) metódussal. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Visszaadja a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekérdezi a pointer módot. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Visszaadja a mutatott objektumot, de ellenőrzi, hogy a pointer megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Megkapja a megosztott pointerek számát, amelyek a hivatkozott objektumra mutatnak, beleértve a jelenlegit is. Ellenőrzi, hogy az aktuális pointer megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Visszaadja a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Visszaadja a mutatott objektumot (ha van) vagy nullptr-ot. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Visszaadja a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Visszaadja a mutatott objektumot (ha van) vagy nullptr-ot. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum egy adott típusú vagy annak gyermek típusa-e. A C# 'is' szintaxisát követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a pointer egy másik, mint a saját tulajdonú objektumra mutat-e (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a pointer megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a pointer gyenge módban van-e. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a pointer nem nullptr. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a pointer nullptr-e. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Visszaad referencia a mutatott objektumra. Ellenőrzi, hogy a pointer nem nullptr. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítás szemantika a [SmartPtr](../../system/smartptr/) osztályhoz. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítás szemantika a [SmartPtr](../../system/smartptr/) osztályhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Átmozgatásos hozzárendelés a [SmartPtr](../../system/smartptr/) objektumra. x használhatatlanná válik. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másolásos hozzárendelés a [SmartPtr](../../system/smartptr/) objektumra. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másolásos hozzárendelés a [SmartPtr](../../system/smartptr/) objektumra. Szükséges típuskonverziókat végez. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers pointert rendel a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Pointer értékét nullptr-ra állítja. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a pointer nullptr-ra mutat-e. |
| V\& [operator[]](./operator[]/)(const X\&) const | Hozzáférési operátor kulcstípus konverzióhoz. |
| V\& [operator[]](./operator[]/)(const T\&) const | Hozzáférési operátor. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasing-et (aliasing konstruktor által létrehozott) a pointerről, biztosítva, hogy (ha megosztott) kezelje vagy (ha gyenge) kövesse ugyanazt az objektumot, amire mutat. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A pointert nullptr-ra állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a pointer módot. Megváltoztathatja a hivatkozott objektum referenciaszámlálóját. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a [SmartPtr](../../system/smartptr/) objektumot a kívánt módban. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a null-pointer [SmartPtr](../../system/smartptr/) objektumot a kívánt módban. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/)-et, amely a megadott objektumra mutat, vagy nyers pointert konvertál [SmartPtr](../../system/smartptr/)-ra. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstruktor a [SmartPtr](../../system/smartptr/) objektumhoz. Ezután mindkét pointer ugyanarra az objektumra mutat. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstruktor a [SmartPtr](../../system/smartptr/) objektumhoz. Ezután mindkét pointer ugyanarra az objektumra mutat. Típuskonverziót hajt végre, ha engedélyezett. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Áthelyezéses konstruktor a [SmartPtr](../../system/smartptr/) objektumhoz. Gyakorlatilag két pointert cserél, ha mindkettő ugyanabban a módban van. x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átkonvertálja a hivatkozott tömb típusát egy új, más típusú tömb létrehozásával. Hasznos, ha C#-ban létezik egy tömb típus konverzió, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstrukció lefordításához használják. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a [SmartPtr](../../system/smartptr/)-t, amely a ptr kezdeti értékével megosztja a tulajdoninformációkat, de egy nem kapcsolódó, nem kezelt pointer p-t tárol. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átkonvertálja a pointert más típusra a static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Átkonvertál minden pointer típust [Object](../../system/object/) pointerre. Nem igényli, hogy a Pointee_ típus komplett legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövidítés a [System::TypeInfo](../../system/typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciaszámlálóját és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névterület [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)