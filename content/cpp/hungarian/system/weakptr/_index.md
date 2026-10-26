---
title: WeakPtr
second_title: Aspose.Slides C++ API Referenciája
description: "A System::SmartPtr alosztálya, amely a konstrukció során gyenge módra állítja magát. Kérjük, vegye figyelembe, hogy ez az osztály nem garantálja, hogy példánya mindig gyenge módban marad, mivel a set_Mode() továbbra is elérhető. Ez a típus egy mutató, amely más objektumok törlését kezeli. Halomra helyett a stack-en kell lefoglalni, és függvényeknek értékként vagy const referenciaként kell átadni."
type: docs
weight: 1496
url: /hu/system/weakptr/
---
## WeakPtr osztály

A [System::SmartPtr](../smartptr/) alosztálya, amely a konstrukciókor gyenge módra állítja magát. Kérjük, vegye figyelembe, hogy ez az osztály nem garantálja, hogy példánya mindig gyenge módban marad, mivel a [set_Mode()](../smartptr/set_mode/) továbbra is elérhető. Ez a típus egy mutató, amely más objektumok törlését kezeli. Halomra helyett a stack-en kell lefoglalni, és függvényeknek értékként vagy const referenciaként kell átadni.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| T | Pointee típus. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Az [begin()](../smartptr/begin/) metódushoz való hozzáférő egy alá-függő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ a [begin()](../smartptr/begin/) metódussal rendelkező specializációs típus. |
| auto [begin](../smartptr/begin/)() const | Az [begin()](../smartptr/begin/) metódushoz való hozzáférő egy alá-függő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ a [begin()](../smartptr/begin/) metódussal rendelkező specializációs típus. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | A mutatót a saját típusára konvertálja. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | A mutatót a bázistípusra static_cast használatával konvertálja. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | A mutatót a származtatott típusra dynamic_cast használatával konvertálja. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | A mutatót a származtatott típusra dynamic_cast használatával konvertálja. |
| auto [cbegin](../smartptr/cbegin/)() const | Az [cbegin()](../smartptr/cbegin/) metódushoz való hozzáférő egy alá-függő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ a [cbegin()](../smartptr/cbegin/) metódussal rendelkező specializációs típus. |
| auto [cend](../smartptr/cend/)() const | Az [cend()](../smartptr/cend/) metódushoz való hozzáférő egy alá-függő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ a [cend()](../smartptr/cend/) metódussal rendelkező specializációs típus. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | A mutatót egy másik típusra konvertálja a const_cast használatával a mutatott objektumon. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | A mutatót egy másik típusra konvertálja a dynamic_cast használatával a mutatott objektumon. |
| auto [end](../smartptr/end/)() | Az [end()](../smartptr/end/) metódushoz való hozzáférő egy alá-függő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ a [end()](../smartptr/end/) metódussal rendelkező specializációs típus. |
| auto [end](../smartptr/end/)() const | Az [end()](../smartptr/end/) metódushoz való hozzáférő egy alá-függő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ a [end()](../smartptr/end/) metódussal rendelkező specializációs típus. |
| **bool** [expired](./expired/)() const | Ellenőrzi, hogy a hivatkozott objektum már törölve lett-e. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | A mutatott objektumot adja vissza. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Visszaadja a mutató módját. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Visszaadja a mutatott objektumot, de ellenőrzést végez, hogy a mutató megosztott módban van. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Megadja a hivatkozott objektumra mutató megosztott mutatók számát, beleértve a jelenlegit is. Ellenőrzést végez, hogy az aktuális mutató megosztott módban van. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Visszaadja a hivatkozott objektumot. Ellenőrzést végez, hogy a mutató gyenge módban van. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Visszaadja a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Visszaadja a mutatott objektumot (ha van), vagy nullptr-et. Ugyanaz, mint a [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Visszaadja a hivatkozott objektumot. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Visszaadja a mutatott objektumot (ha van), vagy nullptr-et. Ugyanaz, mint a [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum egy adott típusú vagy annak leszármazottja-e. A C# 'is' szemantikai szabályait követi. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik, a tulajdonos által nem birtokolt objektumra mutat-e (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null-értékű. |
| **bool** [operator!](../smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null-e. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Referencia visszaadása a mutatott objektumra. Ellenőrzést végez, hogy a mutató nem null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítás szemtantikát biztosít a [SmartPtr](../smartptr/) osztályhoz. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítás szemtantikát biztosít a [SmartPtr](../smartptr/) osztályhoz. |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Értéket rendel a gyenge mutatóhoz. A SmartPtr_ adott hozzárendelő operátorát hívja. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Áthelyező-assignálja a [SmartPtr](../smartptr/) objektumot. Az x használhatatlanná válik. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Másoló-assignálja a [SmartPtr](../smartptr/) objektumot. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Másoló-assignálja a [SmartPtr](../smartptr/) objektumot. Szükséges típuskonverziókat végez. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Nyers mutatót rendeli a [SmartPtr](../smartptr/) objektumhoz. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | A mutató értékét nullptr-re állítja. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a gyenge mutató null-e. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Eltávolítja az aliasingot (aliasing konstruktor által létrehozott) a mutatóból, és biztosítja, hogy a mutató (ha megosztott) kezelje vagy (ha gyenge) kövesse azt az objektumot, amelyre mutat. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../smartptr/reset/)() | A mutatót nullptr-re állítja. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Beállítja a mutató módját. Megváltoztathatja a hivatkozott objektum referenciáit. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Létrehozza a szükséges módú [SmartPtr](../smartptr/) objektumot. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Létrehozza a null mutató [SmartPtr](../smartptr/) objektumot a szükséges móddal. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Létrehozza a [SmartPtr](../smartptr/) objektumot, amely a megadott objektumra mutat, vagy konvertálja a nyers mutatót [SmartPtr](../smartptr/)-ra. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Másoló konstrukcióval létrehozza a [SmartPtr](../smartptr/) objektumot. Ezután mindkét mutató ugyanarra az objektumra mutat. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Másoló konstrukcióval létrehozza a [SmartPtr](../smartptr/) objektumot. Ezután mindkét mutató ugyanarra az objektumra mutat. Típuskonverziót végez, ha engedélyezett. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Áthelyező konstrukcióval létrehozza a [SmartPtr](../smartptr/) objektumot. Lényegében felcseréli a két mutatót, ha mindkettő ugyanabban a módban van. Az x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Átkonvertálja a hivatkozott tömb típusát egy új, más típusú tömb létrehozásával. Hasznos, ha C#-ban létezik egy tömb típuskonverzió, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstrukció fordításához használják. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Létrehoz egy [SmartPtr](../smartptr/) objektumot, amely megosztja a tulajdonosi információkat a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt mutatót p tartalmaz. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | A mutatót egy másik típusra konvertálja static_cast használatával a mutatott objektumon. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Bármely mutatótípust [Object](../object/) mutatóra konvertál. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Rövidítés a [System::TypeInfo](../typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Null mutatót hoz létre. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Gyenge mutatót hoz létre a megadott objektumra. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Gyenge mutatót hoz létre, amely a ptr által mutatott ugyanarra a mutatóra hivatkozik. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Gyenge mutatót hoz létre, amely az x által mutatott ugyanarra a mutatóra hivatkozik. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Másoló konstrukcióval hoz létre gyenge mutatót. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Másoló konstrukcióval hoz létre gyenge mutatót. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Áthelyező konstrukcióval hoz létre gyenge mutatót. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciakontáját és törli az objektumot. |

## Típusdefiníciók

| Typedef | Leírás |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Az [SmartPtr](../smartptr/) osztálynak megfelelő alias. |
| [WeakPtr_](./weakptr_/) | Az ön típusának alias. |
| [Pointee_](./pointee_/) | Mutatott típus. |

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)