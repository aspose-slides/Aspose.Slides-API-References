---
title: WriteAsync()
second_title: Aspose.Slides for C++ API Referencia
description: Aszinkron módon ír egy bájtsorozatot az aktuális folyamathoz, a megírt bájtok számával eltolja az aktuális pozíciót ebben a folyamathoz, és figyeli a leállítási kéréseket.
type: docs
weight: 261
url: /hu/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metódus

Aszinkron módon ír egy bájtsorozatot az aktuális folyamathoz, a megírt bájtok számával eltolja az aktuális pozíciót ebben a folyamathoz, és figyeli a leállítási kéréseket.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájtok írásához tartalmazó tömb. |
| offset | **int32_t** | A 0-bázisú index a **buffer** elemben, ahol a írásra szánt alintervallum kezdődik. |
| count | **int32_t** | Az írásra szánt alintervallum elemeinek száma. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | A leállítási kérések figyeléséhez használt token. |

### Visszatérési érték

Egy feladat, amely az aszinkron írási műveletet képviseli.

## Lásd még

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [CancellationToken](../../../system.threading/cancellationtoken/)
* Osztály [FileStream](../)
* Névterület [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)