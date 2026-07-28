---
title: StringCollectionPtr
second_title: Aspose.Slides C++ API hivatkozás
description: Karakterlánc-gyűjtemény mutató a hozzáférési operátorral.
type: docs
weight: 40
url: /hu/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr osztály


String gyűjtemény mutató hozzáférési operátorral.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## Metódusok

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Hozzáférő a [begin()](../../system/smartptr/begin/) metódushoz egy alacsonyabb gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ speciális típus, amely rendelkezik a [begin()](../../system/smartptr/begin/) metódussal. |
| auto [begin](../../system/smartptr/begin/)() const | Hozzáférő a [begin()](../../system/smartptr/begin/) metódushoz egy alacsonyabb gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ speciális típus, amely rendelkezik a [begin()](../../system/smartptr/begin/) metódussal. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót az ős típusra static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a származtatott típusra dynamic_cast segítségével. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a származtatott típusra dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Hozzáférő a [cbegin()](../../system/smartptr/cbegin/) metódushoz egy alacsonyabb gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ speciális típus, amely rendelkezik a [cbegin()](../../system/smartptr/cbegin/) metódussal. |
| auto [cend](../../system/smartptr/cend/)() const | Hozzáférő a [cend()](../../system/smartptr/cend/) metódushoz egy alacsonyabb gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ speciális típus, amely rendelkezik a [cend()](../../system/smartptr/cend/) metódussal. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra const_cast segítségével a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Hozzáférő a [end()](../../system/smartptr/end/) metódushoz egy alacsonyabb gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ speciális típus, amely rendelkezik a [end()](../../system/smartptr/end/) metódussal. |
| auto [end](../../system/smartptr/end/)() const | Hozzáférő a [end()](../../system/smartptr/end/) metódushoz egy alacsonyabb gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ speciális típus, amely rendelkezik a [end()](../../system/smartptr/end/) metódussal. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Lekéri a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekéri a mutató módját. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Lekéri a mutatott objektumot, de ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Visszaadja a megosztott mutatók számát, amelyek a hivatkozott objektumra mutatnak, beleértve a jelenlegit is. Ellenőrzi, hogy a jelenlegi mutató megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Lekéri a jelenleg hivatkozott objektumot (ha van), különben kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Lekéri a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum adott típusú vagy annak gyermek típusa. A C# 'is' szempontjait követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik objektorra mutat, mint a tulajdonolt (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Lekéri a mutatott objektumra való referenciát. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb összehasonlítási szemantikumot biztosít a [SmartPtr](../../system/smartptr/) osztályhoz. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb összehasonlítási szemantikumot biztosít a [SmartPtr](../../system/smartptr/) osztályhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Áthelyező-értékadást végez a [SmartPtr](../../system/smartptr/) objektumra. x használhatatlanná válik. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másoló-értékadást végez a [SmartPtr](../../system/smartptr/) objektumra. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másoló-értékadást végez a [SmartPtr](../../system/smartptr/) objektumra. Szükséges típuskonverziókat hajt végre. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers mutatót rendel a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Beállítja a mutató értékét nullptr-ra. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a mutató nullptr-ra mutat. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | Hozzáférő függvény. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasingot (aliasing konstruktor által létrehozott) a mutatóról, és biztosítja, hogy az (ha megosztott) vagy (ha gyenge) ugyanazt az objektumot kezelje vagy kövesse, amelyre mutat. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A mutatót nullptr-ra állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a mutató módját. Megváltoztathatja a hivatkozott objektum referenciáik számát. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a szükséges módú [SmartPtr](../../system/smartptr/) objektumot. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a null mutatóval rendelkező [SmartPtr](../../system/smartptr/) objektumot a kívánt módban. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a [SmartPtr](../../system/smartptr/)-t, amely a megadott objektumra mutat, vagy átalakítja a nyers mutatót [SmartPtr](../../system/smartptr/)-re. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukciót hoz létre a [SmartPtr](../../system/smartptr/) objektumból. A két mutató ugyanarra az objektumra mutat a művelet után. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukciót hoz létre a [SmartPtr](../../system/smartptr/) objektumból. A két mutató ugyanarra az objektumra mutat a művelet után. Típuskonverziót hajt végre, ha engedélyezett. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Áthelyező konstrukcióval hoz létre egy [SmartPtr](../../system/smartptr/) objektumot. Gyakorlatilag két mutatót cserél, ha mindkettő ugyanabban a módban van. x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átalakítja a hivatkozott tömb típusát egy új, más típusú tömb létrehozásával. Hasznos, ha C#-ban létezik olyan tömb típusú átkonvertálás, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. C# kódrészletek fordításához használják. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a [SmartPtr](../../system/smartptr/) objektumot, amely a ptr kezdeti értékével megosztott tulajdonosi információval rendelkezik, de egy nem kapcsolódó, nem kezelt p mutatót tartalmaz. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra static_cast segítségével a mutatott objektumon. |
| [StringCollectionPtr](./stringcollectionptr/)() | Létrehozza a null mutatót. |
| [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | Létrehozza a mutatót egy adott gyűjteményhez. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Átalakít bármely mutatótípust [Object](../../system/object/) mutatóra. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövidítés a [System::TypeInfo](../../system/typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciaszámlálóját és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névtér [System::Collections::Specialized](../)
* Könyvtár [Aspose.Slides](../../)