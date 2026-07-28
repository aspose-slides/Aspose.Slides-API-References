---
title: "System::Diagnostics"
second_title: "Aspose.Slides C++ API referencia"
description: 
type: docs
weight: 469
url: /hu/system.diagnostics/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [FileVersionInfo](./fileversioninfo/) | Információkat biztosít a fájl verziójáról. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja az osztály függvények argumentumaként való átadásához. |
| [PerformanceCounter](./performancecounter/) | Ál osztály a PerformanceCounter-t használó lefordított kód fordításához. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja az osztály függvények argumentumaként való átadásához. |
| [Process](./process/) | Kapszulázza a folyamat információit és azok manipulációját. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja az osztály függvények argumentumaként való átadásához. |
| [ProcessStartInfo](./processstartinfo/) | Leírja a folyamat indítási paramétereit. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja az osztály függvények argumentumaként való átadásához. |
| [StackFrame](./stackframe/) | Információkat ad a egyetlen stack keretről. Csak MSVS. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja az osztály függvények argumentumaként való átadásához. |
| [StackTrace](./stacktrace/) | Stack keretek gyűjteménye. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja az osztály függvények argumentumaként való átadásához. |
| [Stopwatch](./stopwatch/) | Időmérést tesz lehetővé. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja az osztály függvények argumentumaként való átadásához. |
| [TraceListener](./tracelistener/) | Felület a hibakeresési és nyomkövetési információkra való reagáláshoz. Ennek az osztálynak a példányait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ezen típusból a stacken vagy az operator new segítségével, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és ezt a mutatót használja az osztály függvények argumentumaként való átadásához. |

## Struktúrák

| Struktúra | Leírás |
| --- | --- |
| [Debug](./debug/) | A hibakeresési metódusok gyűjteménye, amely lehetővé teszi a hibainformációk küldését a regisztrált hallgatóknak. Minden kimeneti függvény csak [Debug](./debug/)-ban működik. Ez egy statikus típus, amelynek nincs példány szolgáltatása. Soha ne hozzon létre példányokat semmilyen módon. |
| [Debugger](./debugger/) | [Debugger](./debugger/) felület. Ez egy statikus típus, amelynek nincs példány szolgáltatása. Soha ne hozzon létre példányokat semmilyen módon. |
| [Trace](./trace/) | Felületet biztosít a hibakereső nyomkövetés eléréséhez (ha van). Csak [Debug](./debug/) módban működik. Ez egy statikus típus, amelynek nincs példány szolgáltatása. Soha ne hozzon létre példányokat semmilyen módon. |

## Enumok

| Enum | Leírás |
| --- | --- |
| [ProcessWindowStyle](./processwindowstyle/) | Folyamatablak stílusa. |
| [TraceEventType](./traceeventtype/) | Azonosítja azt az eseménytípust, amely a nyomkövetést okozta. |
| [TraceLevel](./tracelevel/) | Megadja, hogy milyen üzeneteket kell kiadni a [System.Diagnostics.Debug](./debug/), [System.Diagnostics.Trace](./trace/) és a System.Diagnostics.TraceSwitch osztályokhoz. |

## Typedefok

| Typedef | Leírás |
| --- | --- |
| [StopwatchPtr](./stopwatchptr/) | Mutatótípus. |