---
title: Write()
second_title: Referenční příručka API Aspose.Slides pro C++
description: Zapíše zadané pole bajtů do proudu.
type: docs
weight: 404
url: /cs/system.net.security/sslstream/write/
---
## SslStream::Write(const ArrayPtr\<uint8_t\>\&) metoda

Zapíše zadané pole bajtů do proudu.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů k zápisu. |

## SslStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do proudu.

```cpp
void System::Net::Security::SslStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu |
| offset | **int32_t** | 0-založený index prvku v **buffer**, kde podrozsah k zápisu začíná |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&) metoda

Zapíše zadané pole bajtů do proudu.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pole bajtů k zápisu. |

## SslStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metoda

Zapíše zadaný podrozsah bajtů ze zadaného pole bajtů do proudu.

```cpp
void System::Net::Security::SslStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Pole obsahující bajty k zápisu |
| offset | **int32_t** | 0-založený index prvku v **buffer**, kde podrozsah k zápisu začíná |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* třída [SslStream](../)
* jmenný prostor [System::Net::Security](../../)
* knihovna [Aspose.Slides](../../../)