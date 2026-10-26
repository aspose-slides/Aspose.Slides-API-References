---
title: Write()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Zapíše zadaný podřetězec bajtů z určeného pole bajtů do proudu.
type: docs
weight: 209
url: /cs/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Zapíše zadaný podřetězec bajtů z určeného pole bajtů do proudu.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu. |
| offset | **int32_t** | Posun v bajtech v určeném poli. |
| size | **int32_t** | Počet prvků v podřetězci, který se má zapsat. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda


Zapíše zadaný podřetězec bajtů z určeného pole bajtů do proudu.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pohled na pole obsahující bajty k zápisu |
| offset | **int32_t** | Index od nuly prvku v **buffer**, kde podřetězec k zápisu začíná |
| size | **int32_t** | Počet prvků v podřetězci, který se má zapsat |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [NetworkStream](../)
* Jmenný prostor [System::Net::Sockets](../../)
* Knihovna [Aspose.Slides](../../../)