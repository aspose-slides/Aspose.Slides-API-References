---
title: SignData()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vypočítá podpis specifikované vstupní hodnoty.
type: docs
weight: 183
url: /cs/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) metoda

Vypočítá podpis specifikované vstupní hodnoty.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) ke čtení vstupních dat z. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash algoritmus, který se má použít. |

### Návratová hodnota

[RSA](../../rsa/) podpis pro specifikovaná data.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) metoda

Vypočítá podpis specifikované vstupní hodnoty.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Stream, ze kterého se čtou data k podpisu. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash algoritmus, který se má použít. |

### Návratová hodnota

[RSA](../../rsa/) podpis pro specifikovaná data.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) metoda

Vypočítá podpis specifikované vstupní hodnoty.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) ke čtení vstupních dat z. |
| offset | **int32_t** | Počáteční index výřezu vstupního bufferu. |
| count | **int32_t** | Velikost výřezu vstupního bufferu. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash algoritmus, který se má použít. |

### Návratová hodnota

[RSA](../../rsa/) podpis pro specifikovaná data.

## Viz také

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [RSACryptoServiceProvider](../)
* Třída [Stream](../../../system.io/stream/)
* Obor názvů [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)