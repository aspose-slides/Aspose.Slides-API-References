---
title: Read()
second_title: Aspose.Slides pro C++ API Reference
description: Načte zadaný počet bajtů ze streamu a zapíše je do určeného pole bajtů.
type: docs
weight: 391
url: /cs/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Načte daný počet bajtů ze streamu a zapíše je do zadaného pole bajtů.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se zapíšou načtené bajty |
| offset | **int32_t** | Nulová indexová pozice v **buffer**, odkud se začne zapisovat |
| count | **int32_t** | Počet bajtů k načtení |

### Návratová hodnota

Počet načtených bajtů

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Načte daný počet bajtů ze streamu a zapíše je do zadaného pole bajtů.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pole bajtů, do kterého se zapíšou načtené bajty |
| offset | **int32_t** | Nulová indexová pozice v **buffer**, odkud se začne zapisovat |
| count | **int32_t** | Počet bajtů k načtení |

### Návratová hodnota

Počet načtených bajtů

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [SslStream](../)
* Jmenný prostor [System::Net::Security](../../)
* Knihovna [Aspose.Slides](../../../)