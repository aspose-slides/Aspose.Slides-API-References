---
title: ReadAsync()
second_title: Aspose.Slides C++ API referencia
description: Aszinkron módon beolvas egy bájtsorozatot az aktuális adatfolyamból, a beolvasott bájtok számával előre mozgatja a pozíciót a folyamathoz, és figyeli a megszakítási kéréseket.
type: docs
weight: 196
url: /hu/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method


Asynchronously reads a sequence of bytes from the current stream, advances the position within the stream by the number of bytes read, and monitors cancellation requests.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájt tömb, amelybe a beolvasott bájtokat írja. |
| offset | **int32_t** | A 0-bázisú pozíció a **buffer**-ben, ahol a írás elkezdődik. |
| count | **int32_t** | A beolvasandó bájtok száma. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | A token, amely a megszakítási kéréseket figyeli. |

### Visszatérési érték

Egy feladat, amely az aszinkron olvasási műveletet képviseli. A TResult paraméter értéke a pufferré tartozó beolvasott bájtok teljes számát tartalmazza. Az eredményérték kevesebb is lehet, mint a kért bájtok száma, ha a jelenleg rendelkezésre álló bájtok száma kevesebb, mint a kért mennyiség, vagy lehet 0 (nulla), ha a stream vége elérkezett.

## Lásd még

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [CancellationToken](../../../system.threading/cancellationtoken/)
* Osztály [FileStream](../)
* Névterület [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)