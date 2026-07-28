---
title: QueuePtr
second_title: Aspose.Slides for C++ API referencia
description: Queue mutató. Ez a típus egy mutató, amely más objektum törlésének kezelésére szolgál. A stack-en kell lefoglalni, és értékként vagy const referenciaként kell átadni a függvényeknek.
type: docs
weight: 482
url: /hu/system.collections.generic/queueptr/
---
## QueuePtr osztály

[Queue](../queue/) mutató. Ez a típus egy mutató, amely más objektum törlésének kezelésére szolgál. A stack-en kell lefoglalni, és értékként vagy const referenciaként kell átadni a függvényeknek.

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Metódusok

| Method | Leírás |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Az alábbi gyűjtemény [begin()](../../system/smartptr/begin/) metódusához tartozó accessor. Csak akkor fordul le, ha a SmartPtr_ a [begin()](../../system/smartptr/begin/) metódussal specializált típus. |
| auto [begin](../../system/smartptr/begin/)() const | Az alábbi gyűjtemény [begin()](../../system/smartptr/begin/) metódusához tartozó accessor. Csak akkor fordul le, ha a SmartPtr_ a [begin()](../../system/smartptr/begin/) metódussal specializált típus. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót az ősosztály típusára a static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a származtatott típusra a dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Átkonvertálja a mutatót a származtatott típusra a dynamic_cast használatával. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Az alábbi gyűjtemény [cbegin()](../../system/smartptr/cbegin/) metódusához tartozó accessor. Csak akkor fordul le, ha a SmartPtr_ a [cbegin()](../../system/smartptr/cbegin/) metódussal specializált típus. |
| auto [cend](../../system/smartptr/cend/)() const | Az alábbi gyűjtemény [cend()](../../system/smartptr/cend/) metódusához tartozó accessor. Csak akkor fordul le, ha a SmartPtr_ a [cend()](../../system/smartptr/cend/) metódussal specializált típus. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra a const_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra a dynamic_cast használatával a mutatott objektumon. |
| auto [end](../../system/smartptr/end/)() | Az alábbi gyűjtemény [end()](../../system/smartptr/end/) metódusához tartozó accessor. Csak akkor fordul le, ha a SmartPtr_ a [end()](../../system/smartptr/end/) metódussal specializált típus. |
| auto [end](../../system/smartptr/end/)() const | Az alábbi gyűjtemény [end()](../../system/smartptr/end/) metódusához tartozó accessor. Csak akkor fordul le, ha a SmartPtr_ a [end()](../../system/smartptr/end/) metódussal specializált típus. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Visszaadja a mutatott objektumot. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Lekéri a mutató módját. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Visszaadja a mutatott objektumot, azonban ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Lekéri a hivatkozott objektumra mutató megosztott mutatók számát, beleértve a jelenlegit is. Ellenőrzi, hogy a jelenlegi mutató megosztott módban van. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Meghívja a [GetHashCode()](../../system/smartptr/gethashcode/) metódust a mutatott objektumon. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Visszaadja a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Visszaadja a mutatott objektumot (ha van), vagy nullptr értéket. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Visszaadja a hivatkozott objektumot. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Visszaadja a mutatott objektumot (ha van), vagy nullptr értéket. Ugyanaz, mint a [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum adott típusú vagy annak leszármazottja. A C# 'is' szintaxisát követi. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik, a tulajdonositól eltérő objektumra mutat-e (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Ellenőrzi, hogy a mutató null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Visszaad egy referenciát a mutatott objektumra. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Kevesebb-összehasonlítás szemantikát biztosít a [SmartPtr](../../system/smartptr/) osztály számára. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Kevesebb-összehasonlítás szemantikát biztosít a [SmartPtr](../../system/smartptr/) osztály számára. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Mozgatás alapján rendeli hozzá a [SmartPtr](../../system/smartptr/) objektumot. x használhatatlanná válik. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Másolás szerint rendeli hozzá a [SmartPtr](../../system/smartptr/) objektumot. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Másolás szerint rendeli hozzá a [SmartPtr](../../system/smartptr/) objektumot. Végrehajtja a szükséges típuskonverziókat. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Nyers mutatót rendel a [SmartPtr](../../system/smartptr/) objektumhoz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Beállítja a mutató értékét nullptr-ra. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a mutató nullptr-re mutat-e. |
|  [QueuePtr](./queueptr/)() | Null mutatót hoz létre. |
|  [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | Mutatót hoz létre egy adott sorra. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Eltávolítja az aliasing-et (aliasing konstruktor által létrehozott) a mutatóból, biztosítva, hogy a mutató (ha megosztott) kezelje vagy (ha gyenge) nyomon kövesse ugyanazt az objektumot, amelyre mutat. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](../../system/smartptr/reset/)() | A mutató nullptr-re mutat. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Beállítja a mutató módját. A hivatkozott objektum referenciametszáma változhat. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot a kívánt módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy null-mutátor [SmartPtr](../../system/smartptr/) objektumot a kívánt módban. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely a megadott objektumra mutat, vagy nyers mutatót konvertál [SmartPtr](../../system/smartptr/) típusra. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Másolás révén létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Ezután mindkét mutató ugyanarra az objektumra mutat. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Másolás révén létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Ezután mindkét mutató ugyanarra az objektumra mutat. Végrehajtja a típuskonverziót, ha engedélyezett. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Mozgatás révén létrehozza a [SmartPtr](../../system/smartptr/) objektumot. Gyakorlatilag két mutatót cserél, ha mindkettő ugyanabban a módban van. x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Átalakítja a hivatkozott tömb típusát úgy, hogy új, más típusú tömböt hoz létre. Hasznos, ha C#-ban létezik egy tömb típuskörnyezet, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kódkonstrukció lefordítására használják. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Létrehoz egy [SmartPtr](../../system/smartptr/) objektumot, amely a ptr kezdeti értékével megosztja a tulajdonosi információt, de egy nem kapcsolódó, nem kezelt p mutatót tartalmaz. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Átkonvertálja a mutatót más típusra a static_cast használatával a mutatott objektumon. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Bármely mutatótípust [Object](../../system/object/) mutató típusra konvertál. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Rövidítése a [System::TypeInfo](../../system/typeinfo/) objektum lekérésének a Pointee_ típushoz. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Megsemmisíti a [SmartPtr](../../system/smartptr/) objektumot. Ha szükséges, csökkenti a mutatott objektum referenciametszámát és törli az objektumot. |

## Lásd még

* Osztály [SmartPtr](../../system/smartptr/)
* Névterület [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)