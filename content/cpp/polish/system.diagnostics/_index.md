---
title: "System::Diagnostics"
second_title: Aspose.Slides dla C++ – dokumentacja API
description: 
type: docs
weight: 469
url: /pl/system.diagnostics/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Udostępnia informacje o wersji pliku. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [PerformanceCounter](./performancecounter/) | Klasa atrapowa dla kodu przetłumaczonego używającego PerformanceCounter, aby się kompilował. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [Process](./process/) | Enkapsuluje informacje o procesie i ich manipulację. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [ProcessStartInfo](./processstartinfo/) | Opisuje parametry uruchomienia procesu. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [StackFrame](./stackframe/) | Pobiera informacje o pojedynczej ramce stosu. Tylko MSVS. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [StackTrace](./stacktrace/) | Zbiór ramek stosu. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [Stopwatch](./stopwatch/) | Umożliwia pomiar czasu. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
| [TraceListener](./tracelistener/) | Interfejs służący do reagowania na informacje debug i trace. Obiekty tej klasy powinny być przydzielane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani przy użyciu operatora new, ponieważ spowoduje to błędy w czasie wykonywania i/lub naruszenia asercji. Zawsze otaczaj tę klasę wskaźnikiem [System::SmartPtr](../system/smartptr/) i używaj tego wskaźnika do przekazywania jej do funkcji jako argument. |
## Struktury

| Struktura | Opis |
| --- | --- |
| [Debug](./debug/) | Zbiór metod debug umożliwiających wysyłanie informacji debug do zarejestrowanych odbiorców. Wszystkie funkcje wyjściowe działają wyłącznie w [Debug](./debug/). Jest to typ statyczny bez usług instancji. Nigdy nie powinieneś tworzyć jego instancji w żaden sposób. |
| [Debugger](./debugger/) | [Debugger](./debugger/) interfejs. Jest to typ statyczny bez usług instancji. Nigdy nie powinieneś tworzyć jego instancji w żaden sposób. |
| [Trace](./trace/) | Udostępnia interfejs do dostępu do śladu debugera (jeśli istnieje). Działa wyłącznie w trybie [Debug](./debug/). Jest to typ statyczny bez usług instancji. Nigdy nie powinieneś tworzyć jego instancji w żaden sposób. |
## Wyliczenia

| Wyliczenie | Opis |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Styl okna procesu. |
| [TraceEventType](./traceeventtype/) | Określa typ zdarzenia, które spowodowało ślad. |
| [TraceLevel](./tracelevel/) | Określa, które komunikaty wyświetlać dla klas [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) i System.Diagnostics.TraceSwitch. |
## Typedefy

| Typedef | Opis |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Typ wskaźnika. |