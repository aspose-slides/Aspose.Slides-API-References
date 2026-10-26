---
title: Read()
second_title: Aspose.Slides C++ API referencia
description: Adatot olvas a streamből.
type: docs
weight: 14
url: /hu/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus

Adatot olvas a streamből.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Cél adatpuffer. |
| offset | **int32_t** | Eltolás a célpufferben. |
| count | **int32_t** | Olvasandó bájtok száma. |

### Visszatérési érték

A ténylegesen olvasott bájtok száma.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metódus

Adatot olvas a streamből.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Cél adatpuffer. |
| offset | **int32_t** | Eltolás a célpufferben. |
| count | **int32_t** | Olvasandó bájtok száma. |

### Visszatérési érték

A ténylegesen olvasott bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [CryptoStream](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)