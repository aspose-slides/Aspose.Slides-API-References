---
title: ResultValueTask()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert ein leeres, nicht initialisiertes ResultValueTask.
type: docs
weight: 1
url: /de/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() Konstruktor

Konstruiert ein leeres, nicht initialisiertes [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Hinweise

Die Aufgabe ist nicht abgeschlossen und enthält kein Ergebnis. Der Versuch, das Ergebnis abzurufen, führt zu einer Ausnahme.

## ResultValueTask::ResultValueTask(const T\&) Konstruktor

Konstruiert ein abgeschlossenes [ResultValueTask](../) mit dem angegebenen Ergebnis.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| result | const T\& | Der Ergebniswert, der in einer abgeschlossenen Aufgabe verpackt wird. |
## Hinweise

Dies erzeugt eine erfolgreich abgeschlossene Aufgabe, die den Wert sofort zurückgibt.

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) Konstruktor

Konstruiert ein [ResultValueTask](../) aus einem shared pointer zu einem ResultTask<T>.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | Die zu verpackende Aufgabe. Kann für eine leere Aufgabe null sein. |
## Hinweise

Der [ResultValueTask](../) wird den Zustand und das Ergebnis der bereitgestellten Aufgabe darstellen.

## Siehe auch

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Klasse [ResultValueTask](../)
* Namensraum [System::Threading::Tasks](../../)
* Bibliothek [Aspose.Slides](../../../)