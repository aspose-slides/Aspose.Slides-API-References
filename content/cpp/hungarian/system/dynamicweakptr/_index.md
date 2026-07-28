---
title: DynamicWeakPtr
second_title: Aspose.Slides C++ API Referencia
description: Intelligens mutató osztály, amely nyomon követi a tárolt objektum sablonargumentumainak mutató módjait, és minden hozzárendelés után frissíti azokat. Ez a típus egy mutató, amely más objektum törlésének kezelésére szolgál. Halomra (stack) kell allokálni, és függvényeknek érték szerint vagy const referenciaként átadni.
type: docs
weight: 781
url: /hu/system/dynamicweakptr/
---
## DynamicWeakPtr osztály


Intelligens mutató osztály, amely nyomon követi a tárolt objektum sablonargumentumainak mutató módjait, és minden hozzárendelés után frissíti azokat. Ez a típus egy mutató másik objektum törlésének kezelésére. Halomra (stack) kell allokálni, és függvényeknek érték szerint vagy const referenciaként átadni.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Pointee | type. |
| trunkMode | Mode of smart pointer itself, shared or weak. |
| weakLeafs | Indexes of template arguments of stored type which should be set to weak pointer mode. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Hozzáférő a [begin()](../smartptr/begin/) metódushoz egy alapszintű kollekcióban. Csak akkor fordul le, ha a SmartPtr_ specializációs típus a [begin()](../smartptr/begin/) metódussal rendelkezik. |
| auto [begin](../smartptr/begin/)() const | Hozzáférő a [begin()](../smartptr/begin/) metódushoz egy alapszintű kollekcióban. Csak akkor fordul le, ha a SmartPtr_ specializációs típus a [begin()](../smartptr/begin/) metódussal rendelkezik. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Átkonvertálja a mutatót a saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Átkonvertálja a mutatót az ős típusra static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Átkonvertálja a mutatót a leszármazott típusra dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Átkonvertálja a mutatót a leszármazott típusra dynamic_cast használatával. |
| auto [cbegin](../smartptr/cbegin/)() const | Hozzáférő a [cbegin()](../smartptr/cbegin/) metódushoz egy alapszintű kollekcióban. Csak akkor fordul le, ha a SmartPtr_ specializációs típus a [cbegin()](../smartptr/cbegin/) metódussal rendelkezik. |
| auto [cend](../smartptr/cend/)() const | Hozzáférő a [cend()](../smartptr/cend/) metódushoz egy alapszintű kollekcióban. Csak akkor fordul le, ha a SmartPtr_ specializációs típus a [cend()](../smartptr/cend/) metódussal rendelkezik. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra const_cast használatával a mutatott objektumon. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra dynamic_cast használatával a mutatott objektumon. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Létrehoz egy null intelligens mutatót. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Létrehoz egy intelligens mutatót, amely a megadott objektumra mutat. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Másoló konstruktorral hoz létre intelligens mutatót. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Másoló konstruktorral hoz létre intelligens mutatót. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Másoló konstruktorral hoz létre intelligens mutatót. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Mozgató konstruktorral hoz létre intelligens mutatót. |
| auto [end](../smartptr/end/)() | Hozzáférő a [end()](../smartptr/end/) metódushoz egy alapszintű kollekcióban. Csak akkor fordul le, ha a SmartPtr_ specializációs típus a [end()](../smartptr/end/) metódussal rendelkezik. |
| auto [end](../smartptr/end/)() const | Hozzáférő a [end()](../smartptr/end/) metódushoz egy alapszintű kollekcióban. Csak akkor fordul le, ha a SmartPtr_ specializációs típus a [end()](../smartptr/end/) metódussal rendelkezik. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Lekéri a mutatott objektumot. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Lekéri a mutató módját. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Lekéri a mutatott objektumot, de ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Lekéri a megosztott mutatók számát, amelyek a hivatkozott objektumra mutatnak, beleértve a jelenlegit is. Ellenőrzi, hogy a mutató megosztott módban van. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Lekéri a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr-et ad vissza. Ugyanaz, mint a [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Lekéri a hivatkozott objektumot. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr-et ad vissza. Ugyanaz, mint a [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum a megadott típus vagy annak leszármazott típusa-e. A C# 'is' szémantikát követi. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik objektumra mutat-e, mint a tulajdonolt (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Lekéri a mutatott objektum referenciaját. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítási szemantika biztosítása a [SmartPtr](../smartptr/) osztály számára. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítási szemantika biztosítása a [SmartPtr](../smartptr/) osztály számára. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Mozgató-értékadó operátor az intelligens mutatóhoz. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Másoló-értékadó operátor az intelligens mutatóhoz. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Másoló-értékadó operátor az intelligens mutatóhoz. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Értékadó operátor az intelligens mutatóhoz. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | A mutatót null-ra állítja. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy az intelligens mutató null. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Eltávolítja az aliasing-et (aliasing konstruktor által létrehozott) a mutatóból, biztosítva, hogy ugyanazt az objektumot kezelje (ha megosztott) vagy kövesse (ha gyenge), amire mutat. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../smartptr/reset/)() | A mutatót nullptr-re állítja. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Beállítja a mutató módját. Megváltoztathatja a hivatkozott objektum referenciaszámlálóját. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Létrehoz egy [SmartPtr](../smartptr/) objektumot a kívánt módban. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Létrehoz egy null-mutató [SmartPtr](../smartptr/) objektumot a kívánt módban. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Létrehoz egy [SmartPtr](../smartptr/) objektumot a megadott objektumra mutatva, vagy konvertálja a nyers mutatót [SmartPtr](../smartptr/)-re. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Másoló konstruktorral hoz létre egy [SmartPtr](../smartptr/) objektumot. Mindkét mutató ugyanarra az objektumra mutat a művelet után. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Másoló konstruktorral hoz létre egy [SmartPtr](../smartptr/) objektumot. Mindkét mutató ugyanarra az objektumra mutat a művelet után. Típuskonverziót hajt végre, ha engedélyezett. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Mozgató konstruktorral hoz létre egy [SmartPtr](../smartptr/) objektumot. Gyakorlatilag felcseréli a két mutatót, ha mindkettő ugyanabban a módban van. Az x használhatatlan lehet a hívás után. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Átkonvertálja a hivatkozott tömb típusát egy új, más típusú tömb létrehozásával. Hasznos, ha C#-ben olyan tömb típuskonverzió van, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódrészlet konvertálására szolgál. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Létrehoz egy [SmartPtr](../smartptr/) objektumot, amely megosztja a tulajdonosi információt a ptr kiinduló értékével, de egy független, nem kezelt p mutatót tartalmaz. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra static_cast használatával a mutatott objektumon. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Bármely mutató típust átkonvertál [Object](../object/) típusú mutatóra. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Rövid út a [System::TypeInfo](../typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Elpusztítja a [SmartPtr](../smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciaszámlálóját és törli az objektumot. |
## Typedefek

| Typedef | Leírás |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) bázisosztály aliasz. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Saját típus aliasz. |
| [Pointee_](./pointee_/) | Mutatott típus. |

## Lásd még

* Osztály [SmartPtr](../smartptr/)
* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)