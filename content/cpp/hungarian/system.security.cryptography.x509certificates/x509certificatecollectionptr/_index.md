---
title: X509CertificateCollectionPtr
second_title: Aspose.Slides for C++ API Referencia
description: Mutató X509 tanúsítványok gyűjteményéhez. Ez a típus egy mutató, amely más objektumok törlését kezeli. Veremben kell lefoglalni, és a függvényeknek értékként vagy const referenciaként kell átadni.
type: docs
weight: 92
url: /hu/system.security.cryptography.x509certificates/x509certificatecollectionptr/
---
## X509CertificateCollectionPtr osztály

Pointer to collection of X509 certificates. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class X509CertificateCollectionPtr : public System::SmartPtr<X509CertificateCollection>
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Az [begin()](../../system/smartptr/begin/) metódus hozzáférője egy alapszintű gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely [begin()](../../system/smartptr/begin/) metódussal rendelkezik. |
| auto [begin](../../system/smartptr/begin/)() const | Az [begin()](../../system/smartptr/begin/) metódus hozzáférője egy alapszintű gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely [begin()](../../system/smartptr/begin/) metódussal rendelkezik. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót az ős típusra static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a származtatott típusra dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a származtatott típusra dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Az [cbegin()](../../system/smartptr/cbegin/) metódus hozzáférője egy alapszintű gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely [cbegin()](../../system/smartptr/cbegin/) metódussal rendelkezik. |
| auto [cend](../../system/smartptr/cend/)() const | Az [cend()](../../system/smartptr/cend/) metódus hozzáférője egy alapszintű gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely [cend()](../../system/smartptr/cend/) metódussal rendelkezik. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átkonvertálja a mutatót más típusra const_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a mutatót más típusra dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Az [end()](../../system/smartptr/end/) metódus hozzáférője egy alapszintű gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely [end()](../../system/smartptr/end/) metódussal rendelkezik. |
| auto [end](../../system/smartptr/end/)() const | Az [end()](../../system/smartptr/end/) metódus hozzáférője egy alapszintű gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely [end()](../../system/smartptr/end/) metódussal rendelkezik. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Lekéri a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekéri a mutató módját. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Lekéri a mutatott objektumot, de ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Lekéri a hivatkozott objektumra mutató megosztott mutatók számát, beleértve a jelenlegit is. Ellenőrzi, hogy a jelenlegi mutató megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Lekéri a jelenleg hivatkozott objektumot (ha létezik), vagy kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Lekéri a mutatott objektumot (ha létezik), vagy nullptr. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Lekéri a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Lekéri a mutatott objektumot (ha létezik), vagy nullptr. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum egy adott típusú-e vagy annak leszármazottja. A C# 'is' szintaxisát követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik (nem a tulajdonában lévő) objektumra mutat-e (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Lekéri a mutatott objektum referenciáját. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítási szemantikai logikát biztosít a [SmartPtr](../../system/smartptr/) osztályhoz. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítási szemantikai logikát biztosít a [SmartPtr](../../system/smartptr/) osztályhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Áthelyezi és értékadja a [SmartPtr](../../system/smartptr/) objektumot. x használhatatlanná válik. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másolatként értékadja a [SmartPtr](../../system/smartptr/) objektumot. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másolatként értékadja a [SmartPtr](../../system/smartptr/) objektumot. Végrehajtja a szükséges típuskonverziókat. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers mutatót rendel a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Beállítja a mutató értékét nullptr-ra. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a mutató nullptr-ra mutat-e. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\& [operator[]](./operator[]/)(int) const | Hozzáférő. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasinget (aliasing konstruktor által létrehozott) a mutatóból, és biztosítja, hogy (ha megosztott) kezelje vagy (ha gyenge) kövesse azt az objektumot, amelyre mutat. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A mutatót nullptr-ra állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a mutató módját. Megváltoztathatja a hivatkozott objektum referenciáit. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha létezik). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot a kívánt módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy null-pointer [SmartPtr](../../system/smartptr/) objektumot a kívánt módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely a megadott objektumra mutat, vagy konvertálja a nyers mutatót [SmartPtr](../../system/smartptr/)-re. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másolás konstrukcióval létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Mindkét mutató ugyanarra az objektumra mutat a művelet után. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másolás konstrukcióval létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Mindkét mutató ugyanarra az objektumra mutat a művelet után. Típuskonverziót hajt végre, ha engedélyezett. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Áthelyező konstrukcióval hoz létre egy [SmartPtr](../../system/smartptr/) objektumot. Gyakorlatilag két mutatót cserél, ha mindkettő ugyanabban a módban van. x használhatatlan lehet a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átkonvertálja a hivatkozott tömb típusát úgy, hogy egy új, más típusú tömböt hoz létre. Hasznos, ha C#-ban létezik egy tömb típus konverzió, amelyet C++ nem támogat. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstrukció lefordításához használják. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely megosztja a tulajdonjog információkat a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt p mutatót tárol. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átkonvertálja a mutatót más típusra static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Átkonvertál bármilyen mutatótípust [Object](../../system/object/) mutatóra. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövid út a [System::TypeInfo](../../system/typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)() | Null pointer konstruktor. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509CertificateCollection](../x509certificatecollection/)\>\&) | Konstruktor. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciaszámát és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névtere [System::Security::Cryptography::X509Certificates](../)
* Könyvtár [Aspose.Slides](../../)