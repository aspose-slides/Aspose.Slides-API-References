---
title: Read()
second_title: Aspose.Slides for C++ API referenciája
description: A megadott számú bájtot olvassa a folyamatról, és a megadott bájt tömbbe írja.
type: docs
weight: 391
url: /hu/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

A megadott számú bájtot olvassa a folyamatról, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájt tömb, amelybe az olvasott bájtokat írja |
| offset | **int32_t** | **buffer** belül a 0-bázisú pozíció, ahol az írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

A megadott számú bájtot olvassa a folyamatról, és a megadott bájt tömbbe írja.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájt tömb, amelybe az olvasott bájtokat írja |
| offset | **int32_t** | **buffer** belül a 0-bázisú pozíció, ahol az írás kezdődik |
| count | **int32_t** | A beolvasandó bájtok száma |

### Visszatérési érték

A beolvasott bájtok száma

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [SslStream](../)
* Névtér [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)