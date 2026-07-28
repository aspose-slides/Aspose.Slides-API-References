---
title: SignData()
second_title: Aspose.Slides C++ API Referenciája
description: Kiszámítja a megadott bemeneti érték aláírását.
type: docs
weight: 183
url: /hu/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method


Kiszámítja a megadott bemeneti érték aláírását.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) a bemeneti adat olvasásához. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Használni kívánt hash algoritmus. |

### Visszatérési érték

[RSA](../../rsa/) aláírás a megadott adatokhoz.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method


Kiszámítja a megadott bemeneti érték aláírását.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Az aláírandó adatot olvasó adatfolyam. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Használni kívánt hash algoritmus. |

### Visszatérési érték

[RSA](../../rsa/) aláírás a megadott adatokhoz.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method


Kiszámítja a megadott bemeneti érték aláírását.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) a bemeneti adat olvasásához. |
| offset | **int32_t** | Bemeneti puffer szelet kezdő indexe. |
| count | **int32_t** | Bemeneti puffer szelet mérete. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Használni kívánt hash algoritmus. |

### Visszatérési érték

[RSA](../../rsa/) aláírás a megadott adatokhoz.

## Kapcsolódó

* Típusdefiníció [ByteArrayPtr](../../../system/bytearrayptr/)
* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [RSACryptoServiceProvider](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)