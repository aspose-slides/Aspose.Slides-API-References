---
title: ResultValueTask()
second_title: Aspose.Slides for C++ API Referenciája
description: Létrehoz egy üres, nem inicializált ResultValueTask.
type: docs
weight: 1
url: /hu/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() konstruktor


Létrehoz egy üres, nem inicializált [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Megjegyzések



A feladat nincs befejezve, és nem tartalmaz eredményt. Az eredmény lekérdezésének megkísérlése kivételt dob. 

## ResultValueTask::ResultValueTask(const T\&) konstruktor


Létrehoz egy befejezett [ResultValueTask](../)-t a megadott eredménnyel.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| result | const T\& | A befejezett feladatba csomagolandó eredményérték. |
## Megjegyzések



Ez egy sikeresen befejezett feladatot hoz létre, amely azonnal visszaadja az értéket. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) konstruktor


Létrehoz egy [ResultValueTask](../)-t egy ResultTask<T> megosztott mutatóból.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | A becsomagolandó feladat. Üres feladathoz lehet null. |
## Megjegyzések



A [ResultValueTask](../) fogja képviselni a megadott feladat állapotát és eredményét. 

## Lásd még

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Osztály [ResultValueTask](../)
* Névtér [System::Threading::Tasks](../../)
* Könyvtár [Aspose.Slides](../../../)