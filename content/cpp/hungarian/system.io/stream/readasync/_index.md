---
title: ReadAsync()
second_title: Aspose.Slides C++ API referencia
description: Aszinkron módon olvas egy bájtsorozatot az aktuális streamebből, a beolvasott bájtok számával eltolja a pozíciót a streamben, és figyeli a leállítási kéréseket.
type: docs
weight: 40
url: /hu/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Aszinkron módon olvas egy bájtsorozatot az aktuális streamebből, a beolvasott bájtok számával eltolja a pozíciót a streamben, és figyeli a leállítási kéréseket.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájt tömb, amelybe a beolvasott bájtok íródnak. |
| offset | **int32_t** | A 0-bázisú pozíció a **buffer**-ben, ahol az írás megkezdődik. |
| count | **int32_t** | A beolvasandó bájtok száma. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | A token, amely a leállítási kéréseket figyeli. |

### Visszatérési érték

Egy feladat, amely az aszinkron olvasási műveletet képviseli. A TResult paraméter értéke tartalmazza a pufférbe beolvasott bájtok teljes számát. Az eredményérték kisebb lehet a kért bájtok számánál, ha a jelenleg elérhető bájtok száma kisebb a kért mennyiségnél, vagy 0 (nulla) lehet, ha a stream vége elérkezett.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Aszinkron módon olvas egy bájtsorozatot az aktuális streamebből, a beolvasott bájtok számával eltolja a pozíciót a streamben, és figyeli a leállítási kéréseket.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájt tömb, amelybe a beolvasott bájtok íródnak. |
| offset | **int32_t** | A 0-bázisú pozíció a **buffer**-ben, ahol az írás megkezdődik. |
| count | **int32_t** | A beolvasandó bájtok száma. |

### Visszatérési érték

Egy feladat, amely az aszinkron olvasási műveletet képviseli. A TResult paraméter értéke tartalmazza a pufférbe beolvasott bájtok teljes számát. Az eredményérték kisebb lehet a kért bájtok számánál, ha a jelenleg elérhető bájtok száma kisebb a kért mennyiségnél, vagy 0 (nulla) lehet, ha a stream vége elérkezett.

## Lásd még

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [CancellationToken](../../../system.threading/cancellationtoken/)
* Osztály [Stream](../)
* Névterület [System::IO](../../)
* Library [Aspose.Slides](../../../)