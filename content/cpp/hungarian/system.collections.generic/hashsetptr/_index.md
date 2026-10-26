---
title: HashSetPtr
second_title: Aspose.Slides C++ API referenciája
description: Mutató a HashSet hivatkozások megtartásához. Ez a típus egy pointer, amely más objektumok törlését kezeli. A veremben kell lefoglalni, és értékként vagy const referenciaként kell átadni a függvényeknek.
type: docs
weight: 235
url: /hu/system.collections.generic/hashsetptr/
---
## HashSetPtr osztály

Pointer to keep [HashSet](../hashset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## Metódusok

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Az alatta lévő gyűjtemény [begin()](../../system/smartptr/begin/) metódusának accessor-a. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [begin()](../../system/smartptr/begin/) metódussal rendelkezik. |
| auto [begin](../../system/smartptr/begin/)() const | Az alatta lévő gyűjtemény [begin()](../../system/smartptr/begin/) metódusának accessor-a. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [begin()](../../system/smartptr/begin/) metódussal rendelkezik. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átalakítja a mutatót a saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átalakítja a mutatót az ős típusra static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átalakítja a mutatót a származtatott típusra dynamic_cast segítségével. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átalakítja a mutatót a származtatott típusra dynamic_cast segítségével. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Az alatta lévő gyűjtemény [cbegin()](../../system/smartptr/cbegin/) metódusának accessor-a. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [cbegin()](../../system/smartptr/cbegin/) metódussal rendelkezik. |
| auto [cend](../../system/smartptr/cend/)() const | Az alatta lévő gyűjtemény [cend()](../../system/smartptr/cend/) metódusának accessor-a. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [cend()](../../system/smartptr/cend/) metódussal rendelkezik. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átalakítja a mutatót más típusra const_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átalakítja a mutatót más típusra dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Az alatta lévő gyűjtemény [end()](../../system/smartptr/end/) metódusának accessor-a. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [end()](../../system/smartptr/end/) metódussal rendelkezik. |
| auto [end](../../system/smartptr/end/)() const | Az alatta lévő gyűjtemény [end()](../../system/smartptr/end/) metódusának accessor-a. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [end()](../../system/smartptr/end/) metódussal rendelkezik. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Lekéri a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekéri a mutató módját. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Lekéri a mutatott objektumot, de ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Lekéri a hivatkozott objektumra mutató megosztott pointerek számát, beleértve a jelenlegit is. Ellenőrzi, hogy a jelenlegi mutató megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Lekéri a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Lekéri a mutatott objektumot (ha van) vagy nullptr-et. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Lekéri a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Lekéri a mutatott objektumot (ha van) vagy nullptr-et. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
|  [HashSetPtr](./hashsetptr/)() | Null mutató konstruktor. |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | Másoló konstruktor. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum egy adott típusú vagy annak leszármazottja. A C# 'is' szintaxisát követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik, nem a tulajdonában lévő objektumra mutat (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Lekéri a mutatott objektum referenciáját. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlító szemantika a [SmartPtr](../../system/smartptr/) osztályhoz. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlító szemantika a [SmartPtr](../../system/smartptr/) osztályhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Átmozgatja a [SmartPtr](../../system/smartptr/) objektumot. x használhatatlan lesz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másolati hozzárendelés a [SmartPtr](../../system/smartptr/) objektumra. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másolati hozzárendelés a [SmartPtr](../../system/smartptr/) objektumra. Szükséges típuskonverziókat végez. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers pointert rendeli a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | A mutató értékét nullptr-re állítja. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a mutató nullptr-re mutat. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasolást (aliasing konstruktor által létrehozott) a mutatóról, és biztosítja, hogy ugyanazt az objektumot kezelje (ha megosztott) vagy kövesse (ha gyenge), amelyre mutat. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A mutatót nullptr-re állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a mutató módját. Megváltoztathatja a hivatkozott objektum referenciaszámlálóit. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot a szükséges módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy null mutató [SmartPtr](../../system/smartptr/) objektumot a szükséges módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/)-t, amely a megadott objektumra mutat, vagy nyers pointert konvertál [SmartPtr](../../system/smartptr/)-vá. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukcióval hoz létre egy [SmartPtr](../../system/smartptr/) objektumot. Ezután mindkét mutató ugyanarra az objektumra mutat. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukcióval hoz létre egy [SmartPtr](../../system/smartptr/) objektumot. Ezután mindkét mutató ugyanarra az objektumra mutat. Típuskicserélést végez, ha engedélyezett. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Mozgatási konstrukcióval hoz létre egy [SmartPtr](../../system/smartptr/) objektumot. Gyakorlatilag két mutatót cserél, ha mindkettő ugyanabban a módban van. x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átkonvertálja a hivatkozott tömb típusát egy új, eltérő típusú tömb létrehozásával. Hasznos, ha a C#-ban létezik egy tömb típuskonverzió, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstruktum lefordítására használják. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/)-t, amely megosztja a tulajdonjogi információkat az ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt p pointert tartalmaz. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átalakítja a mutatót más típusra static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Bármely mutatótípust [Object](../../system/object/) mutatóra konvertál. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövidítés a [System::TypeInfo](../../system/typeinfo/) objektum eléréséhez a Pointee_ típushoz. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciaszámlálóját és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)