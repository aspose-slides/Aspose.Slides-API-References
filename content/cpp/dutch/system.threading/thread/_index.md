---
title: Thread
second_title: Aspose.Slides voor C++ API-referentie
description: "Thread-implementatie. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject()-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Omhul altijd deze klasse in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 209
url: /nl/system.threading/thread/
---
## Thread klasse

[Thread](./) implementatie. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Omsluit deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class Thread : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Abort](./abort/)() | Annuleert thread. Niet geïmplementeerd. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetalvergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetalvergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | Haalt de threadcultuur op. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | Haalt het object op dat de huidige thread beschrijft. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | Haalt de gebruikersinterfacecultuur op die door de thread wordt gebruikt. |
| **bool** [get_IsAlive](./get_isalive/)() | Controleert of de thread actief is. |
| **bool** [get_IsBackground](./get_isbackground/)() | Controleert of de thread op de achtergrond draait. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | Controleert of de thread eigendom is van een threadpool. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | Haalt de identifier van de thread op. Kan worden verkregen van het OS, maar als de OS-threadidentifier de int-limieten overschrijdt, kunnen thread-id's overlappen. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | Haalt de threadnaam op. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | Haalt de threadstatus op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | Haalt de identifier van de huidige thread op. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| void [Interrupt](./interrupt/)() | Onderbreekt thread. Niet geïmplementeerd. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Join](./join/)() | Voegt beheerde thread samen. Voert onbeperkt wachten uit indien nodig. |
| **bool** [Join](./join/)(int) | Voegt beheerde thread samen. Voert beperkt wachten uit. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | Voegt beheerde thread samen. Voert beperkt wachten uit. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
| static void [MemoryBarrier](./memorybarrier/)() | Synchroniseert geheugen toegang. |
| [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | Kopieert TLS-gegevens van een andere thread. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentie van waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Stelt de threadcultuur in. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | Stelt de door de thread gebruikte gebruikersinterfacecultuur in. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | Stelt de thread in op achtergrond of voorgrond. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | Stelt de threadnaam in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-sjabloonargument in als zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers te wisselen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| static void [Sleep](./sleep/)(int) | Stopt de huidige thread voor de opgegeven timeout. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | Stopt de huidige thread voor de opgegeven timeout. |
| static void [SpinWait](./spinwait/)(int) | Wacht op een specifiek aantal lusiteraties. |
| void [Start](./start/)() | Start thread met een nul-argumentobject. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Start thread. |
| [Thread](./thread/)() | Constructor. |
| [Thread](./thread/)([ThreadStart](../threadstart/)) | Constructor. |
| [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | Constructor. |
| [Thread](./thread/)([Thread](./)\&) | Kopieerconstructor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| static **bool** [Yield](./yield/)() | Geeft thread CPU tijd vrij. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Verwijdert alle interne datastructuren. |
| virtual  [~Thread](./~thread/)() | Destructor. |

## Opmerkingen

```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
Dit codevoorbeeld produceert de volgende output:
Hoofdthread-ID: 2
Kindthread-ID: 1
*/
```

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Threading](../)
* Bibliotheek [Aspose.Slides](../../)