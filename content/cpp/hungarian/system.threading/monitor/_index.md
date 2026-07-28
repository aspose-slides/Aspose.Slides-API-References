---
title: Monitor
second_title: Aspose.Slides C++ API-referencia
description: A Monitor osztály mechanizmust biztosít, amely szinkronizálja az objektumok hozzáférését.
type: docs
weight: 157
url: /hu/system.threading/monitor/
---
## Monitor osztály

Class [Monitor](./) provides a mechanism that synchronizes access to objects.

```cpp
class Monitor : public System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static void [Enter](./enter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Kizárólagos zárat szerez egy megadott objektumon. |
| static void [Enter](./enter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Kizárólagos zárat szerez a megadott objektumon, és atomikusan beállít egy értéket, amely jelzi, hogy a zárat felvették-e. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat C# [Object.Equals](../../system/object/equals/) szemantika használatával hasonlít össze. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referenciatípusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Értéktípusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static void [Exit](./exit/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Felold egy kizárólagos zárat a megadott objektumon. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső felhasználásra. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektummal társított referenciacsont számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi egyedi objektumok hash-elését. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum egy példány-e a targetType által leírt típusból. A C# 'is' operátor analógiája. |
| static **bool** [IsEntered](./isentered/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Megállapítja, hogy a jelenlegi szál tartja-e a zárat a megadott objektumon. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítás zárolását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C# metódus analógiája. Engedélyezi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadás operátor. Valójában semmit nem másol, csak új objektumot inicializál és lehetővé teszi az alosztályok másolókonstrukcióját. |
| static void [Pulse](./pulse/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Értesíti a várakozó sorban lévő szálat a zárolt objektum állapotának változásáról. Nem implementált. |
| static void [PulseAll](./pulseall/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Értesíti az összes várakozó szálat az objektum állapotának változásáról. Nem implementált. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat referenciával hasonlít össze. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenciával hasonlítja össze az értéktípusú objektumot a nullptr értékkel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetén. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetén. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóra (a megosztott helyett). Lehetővé teszi a mutatók konténerekben gyenge módra való átkapcsolását. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló aktuális értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | [Object.ToString()](../../system/object/tostring/) C# metódus analógiája. Engedélyezi egyedi objektumok stringgé alakítását. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Megpróbál kizárólagos zárat szerezni a megadott objektumon. Nem implementált. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Megpróbál kizárólagos zárat szerezni a megadott objektumon, és atomikusan beállít egy értéket, amely jelzi, hogy a zár fel lett-e véve. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Megpróbál, a megadott számú ezredmásodpercig, kizárólagos zárat szerezni a megadott objektumon. Nem implementált. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Megpróbál, a megadott időtartamra, kizárólagos zárat szerezni a megadott objektumon. Nem implementált. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**\&) | Megpróbál, a megadott időtartamra, kizárólagos zárat szerezni a megadott objektumon, és atomikusan beállít egy értéket, amely jelzi, hogy a zár fel lett-e véve. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**\&) | Megpróbál, a megadott időtartamra, kizárólagos zárat szerezni a megadott objektumon, és atomikusan beállít egy értéket, amely jelzi, hogy a zár fel lett-e véve. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**) | Feloldja az objektum zárolását és blokkolja a jelenlegi szálat, amíg újra fel nem veszi a zárat. Ha a megadott időtúllépés eltelik, a szál a készenléti sorba kerül. Opcionálisan kilép a szinkronizációs tartományból a szinkronizált kontextusban a várakozás előtt, és a várakozás után visszalép a tartományba. Nem implementált. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**) | Feloldja az objektum zárolását és blokkolja a jelenlegi szálat, amíg újra fel nem veszi a zárat. Ha a megadott időtúllépés eltelik, a szál a készenléti sorba kerül. Opcionálisan kilép a szinkronizációs tartományból a szinkronizált kontextusban a várakozás előtt, és a várakozás után visszalép a tartományba. Nem implementált. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Feloldja az objektum zárolását és blokkolja a jelenlegi szálat, amíg újra fel nem veszi a zárat. Ha a megadott időtúllépés eltelik, a szál a készenléti sorba kerül. Nem implementált. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Feloldja az objektum zárolását és blokkolja a jelenlegi szálat, amíg újra fel nem veszi a zárat. Ha a megadott időtúllépés eltelik, a szál a készenléti sorba kerül. Nem implementált. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Feloldja az objektum zárolását és blokkolja a jelenlegi szálat, amíg újra fel nem veszi a zárat. Nem implementált. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Megjegyzések

```cpp
#include "system/threading/monitor.h"
#include "system/threading/thread.h"
#include "system/smart_ptr.h"
#include "system/string.h"
#include <iostream>
#include <vector>

int main()
{
  using namespace System::Threading;

  const auto threadsCount = 3;
  std::cout << "Threads count: " << threadsCount << std::endl;
  auto locker = System::MakeObject<System::Object>();
  int x = 0;

  std::vector<System::SharedPtr<Thread>> threads;
  threads.reserve(threadsCount);
  for (auto i = 0; i < threadsCount; ++i)
  {
    threads.emplace_back(System::MakeObject<Thread>([&x, &locker]() -> void {
      Monitor::Enter(locker);

      x = 1;
      for (auto i = 0; i < 5; ++i)
      {
        std::cout << Thread::get_CurrentThread()->get_Name() << ": " << x++ << std::endl;
        Thread::Sleep(100);
      }

      Monitor::Exit(locker);
    }));
    threads.back()->set_Name(System::String("Thread " + std::to_string(i)));
    threads.back()->Start();
  }

  Thread::Sleep(threadsCount * 100);

  for (auto& thread : threads)
  {
    thread->Join();
  }

  return 0;
}
/*
Ez a kódrészlet a következő kimenetet állítja elő:
Szálak száma: 3
Szál 0: 1
Szál 0: 2
Szál 0: 3
Szál 0: 4
Szál 0: 5
Szál 1: 1
Szál 1: 2
Szál 1: 3
Szál 1: 4
Szál 1: 5
Szál 2: 1
Szál 2: 2
Szál 2: 3
Szál 2: 4
Szál 2: 5
*/
```

## Lásd még

* Osztály [Object](../../system/object/)
* Névterület [System::Threading](../)
* Könyvtár [Aspose.Slides](../../)