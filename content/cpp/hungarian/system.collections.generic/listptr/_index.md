---
title: ListPtr
second_title: Aspose.Slides C++ API referencia
description: Lista mutató hozzáférési operátorokkal. Ez a típus egy mutató, amely más objektum törlését kezeli. A stacken kell lefoglalni, és érték vagy const referencia szerint kell átadni a függvényeknek.
type: docs
weight: 456
url: /hu/system.collections.generic/listptr/
---
## ListPtr osztály


[List](../list/) mutató hozzáférési operátorokkal. Ez a típus egy mutató, amely más objektum törlését kezeli. A stacken kell lefoglalni, és érték vagy const referencia alapján kell átadni a függvényeknek.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## Metódusok

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Hozzáférés a [begin()](../../system/smartptr/begin/) metódushoz egy alacsonyabb szintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ olyan specializációs típus, amely rendelkezik [begin()](../../system/smartptr/begin/) metódussal. |
| auto [begin](../../system/smartptr/begin/)() const | Hozzáférés a [begin()](../../system/smartptr/begin/) metódushoz egy alacsonyabb szintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ olyan specializációs típus, amely rendelkezik [begin()](../../system/smartptr/begin/) metódussal. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót az ős típusra static_cast segítségével. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a leszármazott típusra dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a leszármazott típusra dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Hozzáférés a [cbegin()](../../system/smartptr/cbegin/) metódushoz egy alacsonyabb szintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ olyan specializációs típus, amely rendelkezik [cbegin()](../../system/smartptr/cbegin/) metódussal. |
| auto [cend](../../system/smartptr/cend/)() const | Hozzáférés a [cend()](../../system/smartptr/cend/) metódushoz egy alacsonyabb szintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ olyan specializációs típus, amely rendelkezik [cend()](../../system/smartptr/cend/) metódussal. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átkonvertálja a mutatót másik típusra a const_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a mutatót másik típusra a dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Hozzáférés a [end()](../../system/smartptr/end/) metódushoz egy alacsonyabb szintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ olyan specializációs típus, amely rendelkezik [end()](../../system/smartptr/end/) metódussal. |
| auto [end](../../system/smartptr/end/)() const | Hozzáférés a [end()](../../system/smartptr/end/) metódushoz egy alacsonyabb szintű gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ olyan specializációs típus, amely rendelkezik [end()](../../system/smartptr/end/) metódussal. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Visszaadja a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekéri a mutató módját. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Visszaadja a mutatott objektumot, de ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Visszaadja a hivatkozott objektumra mutató megosztott mutatók számát, beleértve a jelenlegit is. Ellenőrzi, hogy a mutató megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Lekéri a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr-ot ad vissza. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Lekéri a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr-ot ad vissza. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum egy adott típusú vagy annak leszármazottja-e. A C# 'is' szintaxisát követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik objektorra mutat-e, mint a saját (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| [ListPtr](./listptr/)(std::nullptr_t) | Null mutató inicializálása. |
| [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | Mutató inicializálása a megadott listára. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Visszaadja a mutatott objektum referenciaját. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb összehasonlítási szemantikumot biztosít a [SmartPtr](../../system/smartptr/) osztályhoz. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb összehasonlítási szemantikumot biztosít a [SmartPtr](../../system/smartptr/) osztályhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Áthelyezi a [SmartPtr](../../system/smartptr/) objektumot. x használhatatlanná válik. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másolás hozzárendelése a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másolás hozzárendelése a [SmartPtr](../../system/smartptr/) objektumhoz. Elvégzi a szükséges típus konverziókat. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers mutató hozzárendelése a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | A mutató értékét nullptr-ra állítja. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a [List](../list/) mutató null. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | Hozzáférés. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | Hozzáférés. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasingot (aliasing konstruktor által létrehozott) a mutatóból, biztosítja, hogy (ha megosztott) kezelje vagy (ha gyenge) kövesse a mutatott ugyanazt az objektumot. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A mutatót nullptr-ra állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a mutató módját. Megváltoztathatja a hivatkozott objektum referenciáit. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a szükséges módú [SmartPtr](../../system/smartptr/) objektumot. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a szükséges módú null mutató [SmartPtr](../../system/smartptr/) objektumot. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a [SmartPtr](../../system/smartptr/) objektumot a megadott objektumra mutatva, vagy átalakítja a nyers mutatót [SmartPtr](../../system/smartptr/)-re. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másolás konstrukcióval létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Mindkét mutató ugyanarra az objektumra mutat. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másolás konstrukcióval létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Mindkét mutató ugyanarra az objektumra mutat. Típuskonverziót végez, ha engedélyezett. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Mozgás konstrukcióval létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Gyakorlatilag kicseréli a két mutatót, ha ugyanabban a módban vannak. x használhatatlanná válhat a hívás után. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átalakítja a hivatkozott tömb típusát egy új, más típusú tömb létrehozásával. Hasznos, ha C#-ban létezik egy tömb típuskast, ami C++-ban nem támogatott. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstrukció lefordításához használják. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely megosztja a tulajdonosi információkat a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt p mutatót tartalmaz. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átkonvertálja a mutatót másik típusra a static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Bármely mutató típust [Object](../../system/object/) mutatóvá konvertál. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövidítés a [System::TypeInfo](../../system/typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciaszámlálóját és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)