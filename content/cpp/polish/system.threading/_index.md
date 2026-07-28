---
title: "System::Threading"
second_title: Aspose.Slides dla C++ – dokumentacja API
description: 
type: docs
weight: 1002
url: /pl/system.threading/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Zdarzenie informujące oczekujący wątek, które resetuje się automatycznie. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [CancellationToken](./cancellationtoken/) | Rozgłasza powiadomienie, że operacje powinny zostać anulowane. Ta klasa zapewnia mechanizm współdziałającego anulowania między wątkami, umożliwiając jednemu wątkowi powiadomienie innych, że operacja powinna zostać anulowana. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | Reprezentuje rejestrację dla wywołania zwrotnego tokenu anulowania. |
| [CancellationTokenSource](./cancellationtokensource/) | Źródło tokenu anulowania, które może być użyte do wywołania powiadomień o anulowaniu. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Zdarzenie, które może być wysłane do oczekującego wątku. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [Interlocked](./interlocked/) | Udostępnia API dla operacji wątkowo-bezpiecznych. Jest to typ statyczny bez usług instancji. Nigdy nie powinieneś tworzyć jego instancji w żaden sposób. |
| [ManualResetEvent](./manualresetevent/) | Zdarzenie informujące oczekujący wątek, które nie resetuje się automatycznie. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [Monitor](./monitor/) | Klasa [Monitor](./monitor/) zapewnia mechanizm synchronizujący dostęp do obiektów. |
| [Mutex](./mutex/) | [Mutex](./mutex/) implementacja. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) implementacja. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [SynchronizationContext](./synchronizationcontext/) | Udostępnia podstawową funkcjonalność propagowania kontekstu synchronizacji pomiędzy różnymi operacjami synchronizacji. |
| [Thread](./thread/) | [Thread](./thread/) implementacja. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) pool API umożliwiające wstawianie zadań do kolejki odczytywanej przez pulę wątków pracowników. Jest to typ statyczny bez usług instancji. Nigdy nie powinieneś tworzyć jego instancji w żaden sposób. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) pool wewnętrzne dane. Jest to typ singleton z zarządzaniem pamięcią realizowanym przez funkcje dostępowe. Nie powinieneś tworzyć jego instancji bezpośrednio. |
| [Timer](./timer/) | [Timer](./timer/) klasa wykonująca element zadania w osobnym wątku po opóźnieniu. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [TimerQueue](./timerqueue/) | Kolejka obsługująca obiekty [Timer](./timer/). To tylko implementacja. Obiekty [Timer](./timer/) rejestrują się tam samodzielnie, nie musisz tego robić, aby je używać – użyj API klasy [Timer](./timer/) zamiast tego. Jest to typ singleton z zarządzaniem pamięcią realizowanym przez funkcje dostępowe. Nie powinieneś tworzyć jego instancji bezpośrednio. |
| [WaitHandle](./waithandle/) | Podstawowa klasa prymitywu oczekującego. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub błędy asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika do przekazywania jej do funkcji jako argument. |
## Struktury

| Struktura | Opis |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) specjalne wartości timeout. Jest to typ statyczny bez usług instancji. Nigdy nie powinieneś tworzyć jego instancji w żaden sposób. |
## Enums

| Enum | Opis |
| --- | --- |
| [ApartmentState](./apartmentstate/) | Ustawia stan apartment wątku. |
| [EventResetMode](./eventresetmode/) | Wskazuje, jak stan zdarzenia jest resetowany. |
| [ThreadState](./threadstate/) | Stan wątku. |
## Typedefy

| Typedef | Opis |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) funkcja z jednym parametrem. |
| [ThreadStart](./threadstart/) | [Thread](./thread/) funkcja bez parametrów. |
| [WaitCallback](./waitcallback/) | Element wywołania zwrotnego wykonywany raz, gdy pojawi się wolne miejsce. |
| [TimerCallback](./timercallback/) | Funkcja wywołania zwrotnego wywoływana przez timer. |
| [wait_handle_t](./wait_handle_t/) | Typ uchwytu. |