---
title: Read()
second_title: Aspose.Slides a C++ API referenciája
description: Ha a csomagolási mód bináris, a megadott számú bájtot olvassa a streame-ből, egyébként a megadott számú karaktert olvassa, és uint8_t típusra konvertálja. Az olvasás eredményét a megadott bájt tömbbe írja. Nem támogatott!
type: docs
weight: 66
url: /hu/system.io/basicstdostreamwrapper/read/
---
## BasicSTDOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


Ha a csomagolási mód bináris, a megadott számú bájtot olvassa a streame-ből, egyébként a megadott számú karaktert olvassa, és **uint8_t** típusra konvertálja. Az olvasás eredményét a megadott bájt tömbbe írja. Nem támogatott!

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájt tömb, amelybe az olvasott bájtok kerülnek |
| offset | **int32_t** | A **buffer**-ben a 0-bázisú pozíció, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

Olvasott bájtok vagy karakterek száma

## BasicSTDOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott számú bájtot olvassa a streame-ből, és a megadott bájt tömbbe írja.

```cpp
virtual int32_t System::IO::BasicSTDOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájt tömb nézet, amelybe az olvasott bájtok kerülnek |
| offset | **int32_t** | A **buffer**-ben a 0-bázisú pozíció, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

Az olvasott bájtok száma

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [BasicSTDOStreamWrapper](../)
* Névtere [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)