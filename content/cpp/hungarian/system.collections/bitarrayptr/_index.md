---
title: BitArrayPtr
second_title: Aspose.Slides C++ API referenciája
description: Mutató a BitArray-hez. Ez a típus egy mutató, amely más objektum törlését kezeli. A stack-en kell lefoglalni, és értékként vagy const referenciaként kell átadni a függvényeknek.
type: docs
weight: 14
url: /hu/system.collections/bitarrayptr/
---
## BitArrayPtr osztály

Mutató a [BitArray](../bitarray/)-hez. Ez a típus egy mutató, amely más objektum törlését kezeli. A stack-en kell lefoglalni, és értékként vagy const referenciaként kell átadni a függvényeknek.

```cpp
class BitArrayPtr : public System::SmartPtr<BitArray>
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Hozzáférés az [begin()](../../system/smartptr/begin/) metódushoz egy alapul szolgáló gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus [begin()](../../system/smartptr/begin/) metódussal. |
| auto [begin](../../system/smartptr/begin/)() const | Hozzáférés az [begin()](../../system/smartptr/begin/) metódushoz egy alapul szolgáló gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus [begin()](../../system/smartptr/begin/) metódussal. |
|  [BitArrayPtr](./bitarrayptr/)() | Inicializálja a null mutatót. |
|  [BitArrayPtr](./bitarrayptr/)(const [SharedPtr](../../system/sharedptr/)\<[BitArray](../bitarray/)\>\&) | Konverziós konstruktor. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót bázistípusra a static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót származtatott típusra a dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót származtatott típusra a dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Hozzáférés az [cbegin()](../../system/smartptr/cbegin/) metódushoz egy alapul szolgáló gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus [cbegin()](../../system/smartptr/cbegin/) metódussal. |
| auto [cend](../../system/smartptr/cend/)() const | Hozzáférés az [cend()](../../system/smartptr/cend/) metódushoz egy alapul szolgáló gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus [cend()](../../system/smartptr/cend/) metódussal. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átkonvertálja a mutatót más típusra a const_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a mutatót más típusra a dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Hozzáférés az [end()](../../system/smartptr/end/) metódushoz egy alapul szolgáló gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus [end()](../../system/smartptr/end/) metódussal. |
| auto [end](../../system/smartptr/end/)() const | Hozzáférés az [end()](../../system/smartptr/end/) metódushoz egy alapul szolgáló gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus [end()](../../system/smartptr/end/) metódussal. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Visszaadja a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Visszaadja a mutató módot. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Visszaadja a mutatott objektumot, de ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Visszaadja a hivatkozott objektumra mutató megosztott mutatók számát, beleértve az aktuálisat is. Ellenőrzi, hogy az aktuális mutató megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Visszaadja a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Visszaadja a mutatott objektumot (ha van) vagy nullptr-ot. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Visszaadja a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Visszaadja a mutatott objektumot (ha van) vagy nullptr-ot. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum a megadott típusú vagy annak gyermek típusa-e. A C# 'is' szémántikát követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató másik objektorra mutat-e, mint a tulajdonolt (aliasing konstruktor által létrehozott). |
| **bool** [IsNull](./isnull/)() const | Ellenőrzi, hogy a megadott érték null-e. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null-e. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Visszaad egy referenciát a mutatott objektumra. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítás szémántikát biztosít a [SmartPtr](../../system/smartptr/) osztály számára. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítás szémántikát biztosít a [SmartPtr](../../system/smartptr/) osztály számára. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Átmozgatja a [SmartPtr](../../system/smartptr/) objektumot. x használhatatlanná válik. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másolja a [SmartPtr](../../system/smartptr/) objektumot. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másolja a [SmartPtr](../../system/smartptr/) objektumot. Végrehajtja a szükséges típuskonverziókat. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers mutatót rendel a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | A mutató értékét nullptr-ra állítja. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a mutató nullptr-re mutat-e. |
| **BitArray::Reference** [operator[]](./operator[]/)(int) const | Bit hozzáférő. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasing-et (aliasing konstruktor által létrehozott) a mutatóból, biztosítja, hogy ugyanarra az objektumra mutasson (ha megosztott) vagy kövesse (ha gyenge). |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A mutatót nullptr-re állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a mutató módot. Módosíthatja a hivatkozott objektum referenciaszámlálóját. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot a szükséges módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy null mutató [SmartPtr](../../system/smartptr/) objektumot a szükséges módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely a megadott objektumra mutat, vagy konvertálja a nyers mutatót [SmartPtr](../../system/smartptr/)-ra. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstruktor [SmartPtr](../../system/smartptr/) objektumhoz. Mindkét mutató ugyanarra az objektumra mutat a konstrukció után. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstruktor [SmartPtr](../../system/smartptr/) objektumhoz. Mindkét mutató ugyanarra az objektumra mutat a konstrukció után. Típuskonverziót hajt végre, ha engedélyezett. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Átmozgató konstruktor [SmartPtr](../../system/smartptr/) objektumhoz. Gyakorlatilag két mutatót cserél, ha mindkettő ugyanabban a módban van. x használhatatlan lehet a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átkonvertálja a hivatkozott tömb típusát egy új, más típusú tömb létrehozásával. Hasznos, ha C#-ban van egy olyan tömbtípus-cast, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstrukció fordításához használják. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/)-t, amely megosztja a tulajdonosi információt a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt mutatót p tartalmaz. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átkonvertálja a mutatót más típusra a static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Átkonvertál bármely mutatót [Object](../../system/object/) mutatóra. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövidítés a [System::TypeInfo](../../system/typeinfo/) objektum eléréséhez a Pointee_ típusra. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciaszámlálóját és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névtér [System::Collections](../)
* Könyvtár [Aspose.Slides](../../)