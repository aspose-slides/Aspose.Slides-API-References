---
title: StackPtr
second_title: Aspose.Slides C++ API referencia
description: Veremmutató. Ez a típus egy mutató, amely más objektum törlését kezeli. A stacken kell lefoglalni, és értékként vagy const referenciaként kell átadni a függvényeknek.
type: docs
weight: 612
url: /hu/system.collections.generic/stackptr/
---
## StackPtr osztály


[Stack](../stack/) mutató. Ez a típus egy mutató, amely más objektum törlését kezeli. A stacken kell elhelyezni, és értékként vagy const referenciaként átadni a függvényeknek.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Elem típus. |

## Módszerek

| Módszer | Leírás |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Az [begin()](../../system/smartptr/begin/) metódus hozzáférője egy alapról összeállított gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik a [begin()](../../system/smartptr/begin/) metódussal. |
| auto [begin](../../system/smartptr/begin/)() const | Az [begin()](../../system/smartptr/begin/) metódus hozzáférője egy alapról összeállított gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik a [begin()](../../system/smartptr/begin/) metódussal. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót ős típusra static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót származtatott típusra dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót származtatott típusra dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Az [cbegin()](../../system/smartptr/cbegin/) metódus hozzáférője egy alapról összeállított gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik a [cbegin()](../../system/smartptr/cbegin/) metódussal. |
| auto [cend](../../system/smartptr/cend/)() const | Az [cend()](../../system/smartptr/cend/) metódus hozzáférője egy alapról összeállított gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik a [cend()](../../system/smartptr/cend/) metódussal. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra const_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Az [end()](../../system/smartptr/end/) metódus hozzáférője egy alapról összeállított gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik a [end()](../../system/smartptr/end/) metódussal. |
| auto [end](../../system/smartptr/end/)() const | Az [end()](../../system/smartptr/end/) metódus hozzáférője egy alapról összeállított gyűjteményhez. Csak akkor fordul le, ha a SmartPtr_ egy specializációs típus, amely rendelkezik a [end()](../../system/smartptr/end/) metódussal. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Visszaadja a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekéri a mutató módját. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Visszaadja a mutatott objektumot, de ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Visszaadja a hivatkozott objektumra mutató megosztott mutatók számát, beleértve a jelenlegit. Ellenőrzi, hogy a jelenlegi mutató megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Visszaadja a jelenleg hivatkozott objektumot (ha van), vagy dob egy kivételt. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Visszaadja a mutatott objektumot (ha van), vagy nullptr-ot. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Visszaadja a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Visszaadja a mutatott objektumot (ha van), vagy nullptr-ot. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum egy adott típusú vagy annak leszármazottja. A C# 'is' szintaxist követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik objektumra mutat-e, mint a saját tulajdonú (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null-e. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Visszaad egy referenciát a mutatott objektumra. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítási szemantikai támogatást biztosít a [SmartPtr](../../system/smartptr/) osztályhoz. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítási szemantikai támogatást biztosít a [SmartPtr](../../system/smartptr/) osztályhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Áthelyezi a [SmartPtr](../../system/smartptr/) objektum hozzárendelését. x használhatatlanná válik. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másolás hozzárendelés a [SmartPtr](../../system/smartptr/) objektumra. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másolás hozzárendelés a [SmartPtr](../../system/smartptr/) objektumra. Végrehajtja a szükséges típuskonverziókat. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers mutatót rendel a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Beállítja a mutató értékét nullptr-ra. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a mutató nullptr-re mutat-e. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasing-ot (aliasing konstruktor által létrehozott) a mutatóról, biztosítva, hogy ugyanazt az objektumot menedzselje (ha megosztott) vagy kövesse (ha gyenge). |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A mutatót nullptr-re állítja. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a mutató módját. Módosíthatja a hivatkozott objektum referenciaszámláit. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot a kívánt módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy null mutató [SmartPtr](../../system/smartptr/) objektumot a kívánt módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely a megadott objektumra mutat, vagy átalakítja a nyers mutatót [SmartPtr](../../system/smartptr/)-ra. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukció a [SmartPtr](../../system/smartptr/) objektumhoz. Mindkét mutató ugyanarra az objektumra mutat a konstrukció után. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másoló konstrukció a [SmartPtr](../../system/smartptr/) objektumhoz. Mindkét mutató ugyanarra az objektumra mutat a konstrukció után. Végrehajtja a típuskonverziót, ha engedélyezett. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Áthelyező konstrukció a [SmartPtr](../../system/smartptr/) objektumhoz. Gyakorlatilag két mutatót cserél, ha mindkettő ugyanabban a módban van. x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átalakítja a hivatkozott tömb típusát egy új, más típusú tömb létrehozásával. Hasznos, ha C#-ban létezik egy tömb típuskonverzió, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstruktus fordításához használják. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely megosztja a tulajdonosi információkat a ptr kezdeti értékével, de egy nem kapcsolódó, nem kezelt mutatót p tartalmaz. |
|  [StackPtr](./stackptr/)() | Null mutatót hoz létre. |
|  [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | Létrehoz egy mutatót, amely egy adott stack-re hivatkozik. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Átalakít bármely mutató típust [Object](../../system/object/) mutatójává. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövidítés a [System::TypeInfo](../../system/typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Szükség esetén csökkenti a mutatott objektum referenciaszámlálóját és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)