---
title: WriteAsync()
second_title: Aspose.Slides C++ API Referencia
description: Aszinkron módon ír egy bájtsorozatot az aktuális adatfolyamba, a megírt bájtok számával eltolja az aktuális pozíciót ebben az adatfolyamban, és figyeli a leállítási kéréseket.
type: docs
weight: 66
url: /hu/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metódus


Aszinkron módon ír egy bájtsorozatot az aktuális adatfolyamba, a megírt bájtok számával eltolja az aktuális pozíciót ebben az adatfolyamban, és figyeli a leállítási kéréseket.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Az írandó bájtokat tartalmazó tömb. |
| offset | **int32_t** | A **buffer** tömbben a 0-alapú index, ahol a írandó al-tartomány kezdődik. |
| count | **int32_t** | Az írandó al-tartomány elemeinek száma. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | A token, amely a leállítási kéréseket figyeli. |

### Visszatérési érték

A aszinkron írási műveletet reprezentáló feladat.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


Aszinkron módon ír egy bájtsorozatot az aktuális adatfolyamba, a megírt bájtok számával eltolja az aktuális pozíciót ebben az adatfolyamban, és figyeli a leállítási kéréseket.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Az írandó bájtokat tartalmazó tömb. |
| offset | **int32_t** | A **buffer** tömbben a 0-alapú index, ahol a írandó al-tartomány kezdődik. |
| count | **int32_t** | Az írandó al-tartomány elemeinek száma. |

### Visszatérési érték

A aszinkron írási műveletet reprezentáló feladat.

## Lásd még

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [CancellationToken](../../../system.threading/cancellationtoken/)
* Osztály [Stream](../)
* Névtere [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)