---
title: X509Certificate2CollectionPtr
second_title: Aspose.Slides C++ API referencia
description: Mutató X509 tanúsítványok gyűjteményéhez. Ez a típus egy mutató, amely más objektumok törlésének kezelésére szolgál. A veremben kell lefoglalni, és értékként vagy const referenciaként kell átadni a függvényeknek.
type: docs
weight: 66
url: /hu/system.security.cryptography.x509certificates/x509certificate2collectionptr/
---
## X509Certificate2CollectionPtr osztály

Pointer to collection of X509 certificates. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class X509Certificate2CollectionPtr : public System::SmartPtr<X509Certificate2Collection>
```

## Metódusok

| Method | Leírás |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Az [begin()](../../system/smartptr/begin/) metódus elérésére szolgáló accessor az alapgyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely [begin()](../../system/smartptr/begin/) metódussal rendelkezik. |
| auto [begin](../../system/smartptr/begin/)() const | Az [begin()](../../system/smartptr/begin/) metódus elérésére szolgáló accessor az alapgyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely [begin()](../../system/smartptr/begin/) metódussal rendelkezik. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót az ős típusra static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a származtatott típusra dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a származtatott típusra dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Az [cbegin()](../../system/smartptr/cbegin/) metódus elérésére szolgáló accessor az alapgyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely [cbegin()](../../system/smartptr/cbegin/) metódussal rendelkezik. |
| auto [cend](../../system/smartptr/cend/)() const | Az [cend()](../../system/smartptr/cend/) metódus elérésére szolgáló accessor az alapgyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely [cend()](../../system/smartptr/cend/) metódussal rendelkezik. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átkonvertálja a mutatót más típusra const_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a mutatót más típusra dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Az [end()](../../system/smartptr/end/) metódus elérésére szolgáló accessor az alapgyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely [end()](../../system/smartptr/end/) metódussal rendelkezik. |
| auto [end](../../system/smartptr/end/)() const | Az [end()](../../system/smartptr/end/) metódus elérésére szolgáló accessor az alapgyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ specializációs típus, amely [end()](../../system/smartptr/end/) metódussal rendelkezik. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Visszaadja a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekéri a mutató módját. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Visszaadja a mutatott objektumot, de állítja, hogy a mutató megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Visszaadja a hivatkozott objektumra mutató megosztott mutatók számát, beleértve a jelenlegit is. Állítja, hogy a jelenlegi mutató megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Visszaadja a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Visszaadja a mutatott objektumot (ha van) vagy nullptr-et. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Visszaadja a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Visszaadja a mutatott objektumot (ha van) vagy nullptr-et. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum adott típusú vagy annak gyermek típusa-e. A C# 'is' szintaxisát követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik, mint a tulajdonolt objektumra mutat-e (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null-e. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Visszaad egy referenciát a mutatott objektumra. Állítja, hogy a mutató nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb összehasonlítási szemantika biztosít a [SmartPtr](../../system/smartptr/) osztály számára. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb összehasonlítási szemantika biztosít a [SmartPtr](../../system/smartptr/) osztály számára. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Mozgatásos hozzárendelést végez a [SmartPtr](../../system/smartptr/) objektumra. x használhatatlan lesz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másolásos hozzárendelést végez a [SmartPtr](../../system/smartptr/) objektumra. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másolásos hozzárendelést végez a [SmartPtr](../../system/smartptr/) objektumra. Szükséges típuskonverziókat hajt végre. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers mutatót rendel a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Beállítja a mutató értékét nullptr-re. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a mutató nullptr-re mutat-e. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate2](../x509certificate2/)\>\& [operator[]](./operator[]/)(size_t) const | Elérő. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasingot (aliasing konstruktor által létrehozott) a mutatóból, biztosítva, hogy (ha megosztott) kezelje vagy (ha gyenge) nyomon kövesse ugyanazt az objektumot, amelyre mutat. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A mutatót nullptr-re állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a mutató módját. Megváltoztathatja a hivatkozott objektum referenciáit. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a szükséges módú [SmartPtr](../../system/smartptr/) objektumot. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a szükséges módú null-pointer [SmartPtr](../../system/smartptr/) objektumot. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a [SmartPtr](../../system/smartptr/)-t, amely a megadott objektumra mutat, vagy átkonvertálja a nyers mutatót [SmartPtr](../../system/smartptr/)-re. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukcióval hoz létre egy [SmartPtr](../../system/smartptr/) objektumot. Mindkét mutató ugyanarra az objektumra mutat a művelet után. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukcióval hoz létre egy [SmartPtr](../../system/smartptr/) objektumot. Mindkét mutató ugyanarra az objektumra mutat a művelet után. Szükség esetén típuskonverziót hajt végre. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Mozgatásos konstrukcióval hoz létre egy [SmartPtr](../../system/smartptr/) objektumot. Gyakorlatilag kicseréli a két mutatót, ha mindkettő azonos módban van. x használhatatlan lehet a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átkonvertálja a hivatkozott tömb típusát egy új, különböző típusú tömb létrehozásával. Hasznos, ha C#-ban van egy tömbtípus-kast, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Inicializál egy üres tömböt. Néhány C# kódkonstrukció lefordításához használják. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehozza a [SmartPtr](../../system/smartptr/)-t, amely megosztja a tulajdonosi információkat a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt mutatót p tárol. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átkonvertálja a mutatót más típusra static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Átkonvertál bármely mutatótípusú mutatót [Object](../../system/object/) mutatóra. Nem igényli a Pointee_ típus teljes meghatározását. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövid út a [System::TypeInfo](../../system/typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)() | Null mutató konstruktor. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate2Collection](../x509certificate2collection/)\>\&) | Konstruktor. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciáit és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névterület [System::Security::Cryptography::X509Certificates](../)
* Könyvtár [Aspose.Slides](../../)