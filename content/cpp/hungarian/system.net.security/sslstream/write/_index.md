---
title: Write()
second_title: Aspose.Slides for C++ API hivatkozás
description: A megadott bájttömböt írja a folyamra.
type: docs
weight: 404
url: /hu/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) metódus


A megadott bájttömböt írja a folyamra.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A írandó bájttömb. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott bájttömbből a megadott alintervallum bájtjait írja a folyamra.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájtokat tartalmazó tömb |
| offset | **int32_t** | A **buffer**-ben lévő elem 0-alapú indexe, ahol a írandó alintervallum kezdődik |
| count | **int32_t** | Az írandó alintervallum elemeinek száma |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) metódus


A megadott bájttömböt írja a folyamra.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A írandó bájttömb. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus


A megadott bájttömbből a megadott alintervallum bájtjait írja a folyamra.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A bájtokat tartalmazó tömb |
| offset | **int32_t** | A **buffer**-ben lévő elem 0-alapú indexe, ahol a írandó alintervallum kezdődik |
| count | **int32_t** | Az írandó alintervallum elemeinek száma |

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [SslStream](../)
* Névtér [System::Net::Security](../../)
* Könyvtár [Aspose.Slides](../../../)