---
title: SmartPtr
second_title: Aspose.Slides C++ API referenciája
description: "Mutató osztály típusok becsomagolásához, amelyek a heap-en vannak allokálva. Használja a memória kezelésére az Object-et öröklő osztályok számára. Ez a mutatótípus intruzív mutató szemantikai elvet követ. A referenciaszámláló vagy az Object-ben, vagy egy számláló struktúrában tárolódik, amely szorosan kapcsolódik az Object példányához. Minden SmartPtr példány egyetlen tulajdonosi csoportot alkot, függetlenül a létrehozás módjától, ami eltér a std::shared_ptr osztály viselkedésétől. A nyers mutató SmartPtr-re konvertálása biztonságos, ha más SmartPtr példányok megosztott hivatkozásokat tartanak a ugyanarra az objektumra. A SmartPtr osztálypéldány két állapotban lehet: megosztott mutató és gyenge mutató. Az objektum életben tartásához a megosztott hivatkozások száma legyen pozitív. A gyenge és a megosztott mutatókat egyaránt használhatja a mutatott objektum elérésére (metódusok hívása, mezők olvasása vagy írása stb.), de a gyenge mutatók nem vesznek részt a megosztott mutató referenciaszámlálásában. Az objektum akkor törlődik, amikor az utolsó „megosztott” SmartPtr mutatója megsemmisül. Ezért ügyeljen arra, hogy ez ne történjen meg, ha nincs más megosztott SmartPtr mutató az objektumra, például objektum létrehozás vagy megsemmisítés során. Használja a System::Object::ThisProtector védőobjektumokat (C++ kódban) vagy a CppCTORSelfReference vagy CppSelfReference attribútumot (C# kódban) a probléma megoldásához. Hasonlóképpen, szüntesse meg a ciklikus hivatkozásokat a System::WeakPtr mutatóosztály vagy a System::SmartPtrMode::Weak mutatómód (C++ kódban) vagy a CppWeakPtr attribútum (C# kódban) használatával. Ha két vagy több objektum egymást „megosztott” mutatókkal hivatkozza, soha nem lesznek törölve. Ha a mutatótípus (gyenge vagy megosztott) futásidőben cserélni kell, használja a System::SmartPtr<T>::set_Mode() metódust vagy a System::DynamicWeakPtr osztályt. A SmartPtr osztály nem tartalmaz virtuális metódusokat. Csak akkor örökölje, ha saját memóriakezelési stratégiát hoz létre. Ez a típus egy mutató más objektumok törlésének kezelésére. Stack-en kell allokálni, és értékkel vagy const referenciával átadni a függvényeknek."
type: docs
weight: 1236
url: /hu/system/smartptr/
---
## SmartPtr osztály

Pointer osztály típusok becsomagolásához, amelyek a kupacra kerülnek allokálásra. Használja a memória kezelésére a [Object](../object/)-t öröklő osztályok számára. Ez a mutatótípus intruzív mutató szemantikát követ. A referenciaszámláló vagy a [Object](../object/)-ben, vagy egy számláló struktúrában tárolódik, amely szorosan kapcsolódik a [Object](../object/) példányhoz. Minden [SmartPtr](./) példány egyetlen tulajdonosi csoportot alkot, függetlenül a létrehozás módjától, ami eltér a std::shared_ptr osztály viselkedésétől. A nyers mutató [SmartPtr](./)-re konvertálása biztonságos, ha más [SmartPtr](./) példányok megosztott hivatkozásokat tartanak a ugyanarra az objektumra. A [SmartPtr](./) osztálypéldány két állapotban lehet: megosztott mutató és gyenge mutató. Az objektum életben tartásához a megosztott hivatkozások száma legyen pozitív. A gyenge és a megosztott mutatókat egyaránt használhatja a mutatott objektum elérésére (metódusok hívása, mezők olvasása vagy írása stb.), de a gyenge mutatók nem vesznek részt a megosztott mutató referenciaszámlálásában. A [Object](../object/) akkor kerül törlésre, amikor az utolsó „megosztott” [SmartPtr](./) mutató megsemmisül. Ezért ügyeljen arra, hogy ez ne történjen meg, ha nincs más megosztott [SmartPtr](./) mutató az objektumra, például objektum létrehozás vagy megsemmisítés során. Használja a System::Object::ThisProtector védőobjektumokat (C++ kódban) vagy a CppCTORSelfReference vagy CppSelfReference attribútumot (C# kódban) a probléma megoldásához. Hasonlóképpen, törje meg a ciklikus hivatkozásokat a [System::WeakPtr](../weakptr/) mutató osztály vagy a [System::SmartPtrMode::Weak](../smartptrmode/) mutató mód (C++ kódban) vagy a CppWeakPtr attribútum (C# kódban) használatával. Ha két vagy több objektum egymást „megosztott” mutatókkal hivatkozza, soha nem lesznek törölve. Ha a mutatótípus (gyenge vagy megosztott) futásidőben cserélni kell, használja a [System::SmartPtr<T>::set_Mode()](./set_mode/) metódust vagy a [System::DynamicWeakPtr](../dynamicweakptr/) osztályt. A [SmartPtr](./) osztály nem tartalmaz virtuális metódusokat. Csak akkor örökölje, ha saját memóriakezelési stratégiát hoz létre. Ez a típus egy mutató más objektumok törlésének kezelésére. Stack-en kell allokálni, és értékkel vagy const referenciával átadni a függvényeknek.

```cpp
template<class T>class SmartPtr
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A mutatott objektum típusa. Lehet [System::Object](../object/) vagy annak alosztálya. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| auto [begin](./begin/)() | Hozzáférés a [begin()](./begin/) metódushoz az alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy olyan specializációs típus, amely rendelkezik a [begin()](./begin/) metódussal. |
| auto [begin](./begin/)() const | Hozzáférés a [begin()](./begin/) metódushoz az alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy olyan specializációs típus, amely rendelkezik a [begin()](./begin/) metódussal. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Átkonvertálja a mutatót a saját típusára. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Átkonvertálja a mutatót az ős típusra static_cast használatával. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Átkonvertálja a mutatót a származtatott típusra dynamic_cast használatával. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Átkonvertálja a mutatót a származtatott típusra dynamic_cast használatával. |
| auto [cbegin](./cbegin/)() const | Hozzáférés a [cbegin()](./cbegin/) metódushoz az alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy olyan specializációs típus, amely rendelkezik a [cbegin()](./cbegin/) metódussal. |
| auto [cend](./cend/)() const | Hozzáférés a [cend()](./cend/) metódushoz az alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy olyan specializációs típus, amely rendelkezik a [cend()](./cend/) metódussal. |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra const_cast használatával a mutatott objektumon. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra dynamic_cast használatával a mutatott objektumon. |
| auto [end](./end/)() | Hozzáférés a [end()](./end/) metódushoz az alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy olyan specializációs típus, amely rendelkezik a [end()](./end/) metódussal. |
| auto [end](./end/)() const | Hozzáférés a [end()](./end/) metódushoz az alatta lévő gyűjteményben. Csak akkor fordul le, ha a SmartPtr_ egy olyan specializációs típus, amely rendelkezik a [end()](./end/) metódussal. |
| [Pointee_](./pointee_/) * [get](./get/)() const | Visszaadja a mutatott objektumot. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Visszaadja a mutató módját. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Visszaadja a mutatott objektumot, de ellenőrzi, hogy a mutató megosztott módban van. |
| int [get_shared_count](./get_shared_count/)() const | Visszaadja a hivatkozott objektumra létező megosztott mutatók számát, beleértve a jelenlegit is. Ellenőrzi, hogy a jelenlegi mutató megosztott módban van. |
| int [GetHashCode](./gethashcode/)() const | Meghívja a [GetHashCode()](./gethashcode/)-t a mutatott objektumon. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Visszaadja a jelenleg hivatkozott objektumot (ha van), vagy kivételt dob. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Visszaadja a mutatott objektumot (ha van), vagy nullptr. Ugyanaz, mint a [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Visszaadja a hivatkozott objektumot. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Visszaadja a mutatott objektumot (ha van), vagy nullptr. Ugyanaz, mint a [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Ellenőrzi, hogy a mutatott objektum egy adott típusú vagy annak leszármazottja-e. A C# 'is' szintaxisát követi. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Ellenőrzi, hogy a mutató egy másik, a tulajdonostól különböző objektumra mutat-e (aliasing konstruktor által létrehozott). |
| **bool** [IsShared](./isshared/)() const | Ellenőrzi, hogy a mutató megosztott módban van-e. |
| **bool** [IsWeak](./isweak/)() const | Ellenőrzi, hogy a mutató gyenge módban van-e. |
| explicit  [operator bool](./operator_bool/)() const | Ellenőrzi, hogy a mutató nem null. |
| **bool** [operator!](./operator_not/)() const | Ellenőrzi, hogy a mutató null-e. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Visszaadja a mutatott objektum referenciáját. Ellenőrzi, hogy a mutató nem null. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Lehetővé teszi a hivatkozott objektum tagjainak elérését. |
| **bool** [operator<](./operator_less/)(Y *) const | Kevesebb összehasonlítási szemantikát biztosít a [SmartPtr](./) osztályhoz. |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Kevesebb összehasonlítási szemantikát biztosít a [SmartPtr](./) osztályhoz. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Áthelyező hozzárendelést végez a [SmartPtr](./) objektumra. x használhatatlanná válik. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Másoló hozzárendelést végez a [SmartPtr](./) objektumra. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Másoló hozzárendelést végez a [SmartPtr](./) objektumra. Elvégzi a szükséges típuskonverziókat. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Nyers mutatót rendel a [SmartPtr](./) objektumhoz. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Beállítja a mutató értékét nullptr-ra. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Ellenőrzi, hogy a mutató nullptr-re mutat-e. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Eltávolítja az aliasing-ot (aliasing konstruktor által létrehozott) a mutatóból, és biztosítja, hogy ugyanazt az objektumot kezelje (ha megosztott) vagy kövesse (ha gyenge), amelyre mutat. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Beállítja a mutatott objektumot. |
| void [reset](./reset/)() | A mutatót nullptr-re állítja. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Beállítja a mutató módját. Módosíthatja a hivatkozott objektum referenciaszámlálóit. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Meghívja a SetTemplateWeakPtr() metódust a mutatott objektumon (ha van). |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Létrehozza a szükséges módú [SmartPtr](./) objektumot. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Létrehozza a szükséges módú null mutató [SmartPtr](./) objektumot. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Létrehozza a [SmartPtr](./) objektumot, amely a megadott objektumra mutat, vagy átkonvertálja a nyers mutatót a [SmartPtr](./)-ra. |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Másolatkonstrukciót végez a [SmartPtr](./) objektumra. Mindkét mutató később ugyanarra az objektumra mutat. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Másolatkonstrukciót végez a [SmartPtr](./) objektumra. Mindkét mutató később ugyanarra az objektumra mutat. Típuskonverziót végez, ha megengedett. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Áthelyező konstrukciót végez a [SmartPtr](./) objektumra. Gyakorlatban kicseréli a két mutatót, ha ugyanabban a módban vannak. x használhatatlanná válhat a hívás után. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Átkonvertálja a hivatkozott tömb típusát egy új, más típusú tömb létrehozásával. Hasznos, ha C#-ban van egy tömb típuskonverzió, amely C++-ban nem támogatott. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Üres tömböt inicializál. Néhány C# kód konstrukció lefordításához használják. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Létrehozza a [SmartPtr](./) objektumot, amely megosztja a tulajdonosi információkat a ptr kezdeti értékével, de egy nem kapcsolódó és nem kezelt mutatót p tartalmaz. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Átkonvertálja a mutatót egy másik típusra static_cast használatával a mutatott objektumon. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Átalakít bármilyen mutató típust a [Object](../object/) mutatóra. Nem igényli, hogy a Pointee_ típus teljes legyen. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Rövidítés a [System::TypeInfo](../typeinfo/) objektum lekéréséhez a Pointee_ típushoz. |
|  [~SmartPtr](./~smartptr/)() | Megsemmisíti a [SmartPtr](./) objektumot. Szükség esetén csökkenti a mutatott objektum referenciaszámlálóját és törli az objektumot. |

## Típusdefiníciók

| Típusdefiníció | Leírás |
| --- | --- |
| [Pointee_](./pointee_/) | Mutatott típus. |
| [SmartPtr_](./smartptr_/) | Specializált okos mutató típus. |
| [ArrayType](./arraytype/) | Ugyanaz, mint a Pointee_, ha egy [System::Array](../array/) specializációja, egyébként void. |
| [ValueType](./valuetype/) | A mutatott tömb tárolótípusa. Csak akkor értelmezhető, ha T egy [System::Array](../array/) specializációja. |

## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)