---
title: GroupCollectionPtr
second_title: Aspose.Slides C++ API Referenciája
description: Csoportgyűjtemény mutató. Ez a típus egy mutató, amely más objektumok törlését kezeli. Stacken kell lefoglalni, és értékkel vagy const referenciával kell átadni a függvényeknek.
type: docs
weight: 53
url: /hu/system.text.regularexpressions/groupcollectionptr/
---
## GroupCollectionPtr osztály


[Group](../group/) gyűjtemény mutató. Ez a típus egy mutató, amely egy másik objektum törlését kezeli. Stacken kell lefoglalni, és értékkel vagy const referenciával kell átadni a függvényeknek.

```cpp
class GroupCollectionPtr : public System::SmartPtr<GroupCollection>
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Az [begin()](../../system/smartptr/begin/) metódus hozzáférője egy alárendelt gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus a [begin()](../../system/smartptr/begin/) metódussal. |
| auto [begin](../../system/smartptr/begin/)() const | Az [begin()](../../system/smartptr/begin/) metódus hozzáférője egy alárendelt gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus a [begin()](../../system/smartptr/begin/) metódussal. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | A mutatót a bázistípusra konvertálja static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | A mutatót a származtatott típusra dynamic_cast segítségével konvertálja. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | A mutatót a származtatott típusra dynamic_cast segítségével konvertálja. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Az [cbegin()](../../system/smartptr/cbegin/) metódus hozzáférője egy alárendelt gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus a [cbegin()](../../system/smartptr/cbegin/) metódussal. |
| auto [cend](../../system/smartptr/cend/)() const | Az [cend()](../../system/smartptr/cend/) metódus hozzáférője egy alárendelt gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus a [cend()](../../system/smartptr/cend/) metódussal. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | A mutatót egy másik típusra konvertálja const_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | A mutatót egy másik típusra konvertálja dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Az [end()](../../system/smartptr/end/) metódus hozzáférője egy alárendelt gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus a [end()](../../system/smartptr/end/) metódussal. |
| auto [end](../../system/smartptr/end/)() const | Az [end()](../../system/smartptr/end/) metódus hozzáférője egy alárendelt gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus a [end()](../../system/smartptr/end/) metódussal. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Lekéri a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekéri a mutató módot. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Lekéri a mutatott objektumot, de ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Lekéri a hivatkozott objektumra mutató megosztott mutatók számát, beleértve a jelenlegit is. Ellenőrzi, hogy a jelenlegi mutató megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Lekéri a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Lekéri a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
|  [GroupCollectionPtr](./groupcollectionptr/)() | Null mutató konstruktor. |
|  [GroupCollectionPtr](./groupcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[GroupCollection](../groupcollection/)\>\&) | Típuskonverziós konstruktor. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum adott típusú vagy annak gyermek típusa-e. A C# 'is' szémantikája szerint. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik objektumra mutat-e, mint a saját tulajdonában lévő (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Lekéri a mutatott objektumra a referenciát. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítási szemantika a [SmartPtr](../../system/smartptr/) osztályhoz. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítási szemantika a [SmartPtr](../../system/smartptr/) osztályhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Mozgó hozzárendelést végez a [SmartPtr](../../system/smartptr/) objektumra. x használhatatlan lesz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másolás hozzárendelést végez a [SmartPtr](../../system/smartptr/) objektumra. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másolás hozzárendelést végez a [SmartPtr](../../system/smartptr/) objektumra. A szükséges típuskonverziókat elvégzi. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers mutatót rendel a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | A mutató értékét nullptr-ra állítja. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a mutató nullptr-ra mutat-e. |
| [GroupPtr](../groupptr/) [operator[]](./operator[]/)(size_t) const | [Group](../group/) hozzáférő. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasing-et (aliasing konstruktor által létrehozott) a mutatóból, és biztosítja, hogy a mutató (ha megosztott) kezelje vagy (ha gyenge) kövesse a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A mutatót nullptr-ra állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a mutató módot. Megváltoztathatja a hivatkozott objektum referenciáit. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot a szükséges módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy null-mutató [SmartPtr](../../system/smartptr/) objektumot a szükséges módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/)-t, amely a megadott objektumra mutat, vagy nyers mutatót konvertál [SmartPtr](../../system/smartptr/) típusra. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másolás konstrukciót hajt végre a [SmartPtr](../../system/smartptr/) objektumra. Ezután mindkét mutató ugyanarra az objektumra mutat. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másolás konstrukció a [SmartPtr](../../system/smartptr/) objektumra. Mindkét mutató ugyanarra az objektumra mutat. Típuskonverziót végez, ha megengedett. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Mozgás konstrukció a [SmartPtr](../../system/smartptr/) objektumra. Gyakorlatilag kicseréli a két mutatót, ha mindkettő ugyanabban a módban van. x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átkonvertálja a hivatkozott tömb típusát egy másik típusú új tömb létrehozásával. Hasznos, ha C#-ban van egy tömb típus átkonvertálás, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kód konstrukció lefordításához használják. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/)-t, amely megosztja a tulajdonjogi információkat a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt mutatót p-t tárol. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | A mutatót egy másik típusra konvertálja static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Bármely mutatótípust [Object](../../system/object/) mutatóra konvertál. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövid út a [System::TypeInfo](../../system/typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciáit és törli az objektumot. |
## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névtér [System::Text::RegularExpressions](../)
* Könyvtár [Aspose.Slides](../../)