---
title: X509ExtensionCollectionPtr
second_title: Aspose.Slides C++ API-referencia
description: Mutató X509 kiterjesztések gyűjteményére. Ez a típus egy pointer, amely más objektumok törlésének kezelésére szolgál. Verembe kell allokálni, és értékként vagy const referenciaként kell átadni a függvényeknek.
type: docs
weight: 170
url: /hu/system.security.cryptography.x509certificates/x509extensioncollectionptr/
---
## X509ExtensionCollectionPtr osztály

Pointer to collection of X509 extensions. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class X509ExtensionCollectionPtr : public System::SmartPtr<X509ExtensionCollection>
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | A [begin()](../../system/smartptr/begin/) metódus accessorja egy alapeszközgyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [begin()](../../system/smartptr/begin/) metódussal rendelkezik. |
| auto [begin](../../system/smartptr/begin/)() const | A [begin()](../../system/smartptr/begin/) metódus accessorja egy alapeszközgyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [begin()](../../system/smartptr/begin/) metódussal rendelkezik. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a pointert saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Statikus átkonvertálás a pointert bázistípusra a static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Dinamikus átkonvertálás a pointert származtatott típusra a dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Dinamikus átkonvertálás a pointert származtatott típusra a dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | A [cbegin()](../../system/smartptr/cbegin/) metódus accessorja egy alapeszközgyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [cbegin()](../../system/smartptr/cbegin/) metódussal rendelkezik. |
| auto [cend](../../system/smartptr/cend/)() const | A [cend()](../../system/smartptr/cend/) metódus accessorja egy alapeszközgyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [cend()](../../system/smartptr/cend/) metódussal rendelkezik. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Const_cast segítségével más típusra konvertálja a pointert a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Dynamic_cast segítségével más típusra konvertálja a pointert a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | A [end()](../../system/smartptr/end/) metódus accessorja egy alapeszközgyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [end()](../../system/smartptr/end/) metódussal rendelkezik. |
| auto [end](../../system/smartptr/end/)() const | A [end()](../../system/smartptr/end/) metódus accessorja egy alapeszközgyűjteményben. Csak akkor fordul le, ha a SmartPtr_ specializációs típus [end()](../../system/smartptr/end/) metódussal rendelkezik. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Lekéri a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekéri a pointer módját. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Lekéri a mutatott objektumot, de ellenőrzi, hogy a pointer megosztott módban van-e. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Lekéri a hivatkozott objektumra mutató megosztott pointerek számát, beleértve a jelenlegit is. Ellenőrzi, hogy a jelenlegi pointer megosztott módban van-e. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Lekéri a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr értéket ad vissza. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Lekéri a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Lekéri a mutatott objektumot (ha van), vagy nullptr értéket ad vissza. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum a megadott típus vagy annak gyermek típusa-e. A C# ‘is’ szintaxisát követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a pointer egy olyan objektumra mutat-e, amely nem a tulajdonos (aliasing konstruktor által létrehozott). |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a pointer megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a pointer gyenge módban van-e. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a pointer nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a pointer null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Referenciát ad a mutatott objektumra. Ellenőrzi, hogy a pointer nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítási szémantika biztosítása a [SmartPtr](../../system/smartptr/) osztályhoz. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítási szémantika biztosítása a [SmartPtr](../../system/smartptr/) osztályhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Move-assignálja a [SmartPtr](../../system/smartptr/) objektumot. x használhatatlanná válik. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Copy-assignálja a [SmartPtr](../../system/smartptr/) objektumot. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Copy-assignálja a [SmartPtr](../../system/smartptr/) objektumot. Végrehajtja a szükséges típuskonverziókat. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers pointert rendel a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Pointer értékét nullptr-ra állítja. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a pointer nullptr-ra mutat-e. |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\>\& [operator[]](./operator[]/)(**int32_t**) const | Accessor. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasing-et (aliasing konstruktor által létrehozott) a pointerről, biztosítva, hogy ugyanarra az objektumra mutasson, amelyet kezel (ha megosztott) vagy követ (ha gyenge). |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | Pointert nullptr-ra állít. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a pointer módját. Megváltoztathatja a hivatkozott objektum referenciaszámlálóját. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a szükséges módú [SmartPtr](../../system/smartptr/) objektumot. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a szükséges módú null-pointer [SmartPtr](../../system/smartptr/) objektumot. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a [SmartPtr](../../system/smartptr/) objektumot a megadott objektumra mutatva, vagy nyers pointert konvertál [SmartPtr](../../system/smartptr/)-re. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstruktorral létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Mindkét pointer ugyanarra az objektumra mutat a konstrukció után. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstruktorral létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Mindkét pointer ugyanarra az objektumra mutat a konstrukció után. Típuskonverziót hajt végre, ha engedélyezett. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Move-konstruktorral hoz létre egy [SmartPtr](../../system/smartptr/) objektumot. Gyakorlatilag két pointert cserél, ha ugyanazon módban vannak. x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Új, különböző típusú tömb létrehozásával konvertálja a hivatkozott tömb típusát. Hasznos, ha C#-ben létezik egy olyan tömbtípus-konverzió, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstrukció lefordítására szolgál. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely megosztja a tulajdonosi információkat a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt pointert p-t tárol. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Statikus cast segítségével más típusra konvertálja a pointert a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Bármely pointer típust átalakít [Object](../../system/object/) pointerre. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Gyorselérés a [System::TypeInfo](../../system/typeinfo/) objektumhoz a Pointee_ típus számára. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)() | Null-pointer konstruktor. |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | Konstruktor. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Ha szükséges, csökkenti a mutatott objektum referenciaszámlálóját és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névtér [System::Security::Cryptography::X509Certificates](../)
* Könyvtár [Aspose.Slides](../../)