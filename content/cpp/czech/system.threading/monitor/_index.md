---
title: Monitor
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Třída Monitor poskytuje mechanismus, který synchronizuje přístup k objektům.
type: docs
weight: 157
url: /cs/system.threading/monitor/
---
## Monitor třída

Třída [Monitor](./) poskytuje mechanismus, který synchronizuje přístup k objektům.

```cpp
class Monitor : public System::Object
```

## Metody

| Method | Popis |
| --- | --- |
| static void [Enter](./enter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Získá výlučný zámek na zadaném objektu. |
| static void [Enter](./enter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Získá výlučný zámek na zadaném objektu a atomicky nastaví hodnotu, která udává, zda byl zámek převzat. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání v plovoucí řádové čárce ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání v plovoucí řádové čárce ve stylu C#, kde jsou dva NaN považovány za rovny, i když podle IEC 60559:1989 NaN není rovno žádné hodnotě, včetně NaN. |
| static void [Exit](./exit/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Uvolňuje výlučný zámek na zadaném objektu. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analogie operátoru C# 'is'. |
| static **bool** [IsEntered](./isentered/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Určuje, zda aktuální vlákno drží zámek na zadaném objektu. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static void [Pulse](./pulse/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Upozorňuje vlákno ve frontě čekání na změnu stavu zamčeného objektu. Není implementováno. |
| static void [PulseAll](./pulseall/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Upozorňuje všechna čekající vlákna na změnu stavu objektu. Není implementováno. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Pokouší se získat výlučný zámek na zadaném objektu. Není implementováno. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **bool**\&) | Pokouší se získat výlučný zámek na zadaném objektu a atomicky nastaví hodnotu, která udává, zda byl zámek převzat. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Pokouší se po zadaný počet milisekund získat výlučný zámek na zadaném objektu. Není implementováno. |
| static **bool** [TryEnter](./tryenter/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Pokouší se po zadanou dobu získat výlučný zámek na zadaném objektu. Není implementováno. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**\&) | Pokouší se po zadanou dobu získat výlučný zámek na zadaném objektu a atomicky nastaví hodnotu, která udává, zda byl zámek převzat. |
| static void [TryEnter](./tryenter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**\&) | Pokouší se po zadanou dobu získat výlučný zámek na zadaném objektu a atomicky nastaví hodnotu, která udává, zda byl zámek převzat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**, **bool**) | Uvolňuje zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Pokud uplyne zadaný časový interval, vlákno vstoupí do fronty připravených. Volitelně opustí synchronizační doménu pro synchronizovaný kontext před čekáním a po získání znovu vstoupí do domény. Není implementováno. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/), **bool**) | Uvolňuje zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Pokud uplyne zadaný časový interval, vlákno vstoupí do fronty připravených. Volitelně opustí synchronizační doménu pro synchronizovaný kontext před čekáním a po získání znovu vstoupí do domény. Není implementováno. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, **int32_t**) | Uvolňuje zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Pokud uplyne zadaný časový interval, vlákno vstoupí do fronty připravených. Není implementováno. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, [TimeSpan](../../system/timespan/)) | Uvolňuje zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Pokud uplyne zadaný časový interval, vlákno vstoupí do fronty připravených. Není implementováno. |
| static **bool** [Wait](./wait/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Uvolňuje zámek na objektu a blokuje aktuální vlákno, dokud zámek znovu nezíská. Není implementováno. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počítadlo slabých referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Poznámky



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
Tento příklad kódu produkuje následující výstup:
Počet vláken: 3
Vlákno 0: 1
Vlákno 0: 2
Vlákno 0: 3
Vlákno 0: 4
Vlákno 0: 5
Vlákno 1: 1
Vlákno 1: 2
Vlákno 1: 3
Vlákno 1: 4
Vlákno 1: 5
Vlákno 2: 1
Vlákno 2: 2
Vlákno 2: 3
Vlákno 2: 4
Vlákno 2: 5
*/
```

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Threading](../)
* Knihovna [Aspose.Slides](../../)