---
title: Read()
second_title: Aspose.Slides C++ API referencia
description: Ha a csomagolási mód bináris, akkor a megadott számú bájtot olvassa a streameből, egyébként a megadott számú karaktert olvas, és uint8_t típusra konvertálja. Az olvasás eredményét a megadott byte tömbbe írja.
type: docs
weight: 66
url: /hu/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


Ha a csomagolási mód bináris, akkor a megadott számú bájtot olvassa a streameből, egyébként a megadott számú karaktert olvas és **uint8_t** típusra konvertálja. Az olvasás eredményét a megadott byte tömbbe írja.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A byte tömb, amelybe az olvasott bájtokat írja |
| offset | **int32_t** | A 0-alapú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

Beolvasott bájtok vagy karakterek száma

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott számú bájtot olvassa a streameből, és a megadott byte tömbbe írja.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A byte tömbnézet, amelybe az olvasott bájtokat írja |
| offset | **int32_t** | A 0-alapú pozíció a **buffer**-ben, ahol a írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

Beolvasott bájtok száma

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [BasicSTDIStreamWrapper](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)