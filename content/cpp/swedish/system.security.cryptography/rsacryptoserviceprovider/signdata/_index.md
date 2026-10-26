---
title: SignData()
second_title: Aspose.Slides för C++ API-referens
description: Beräknar signaturen för det angivna indatavärdet.
type: docs
weight: 183
url: /sv/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) metod

Beräknar signaturen för det angivna indatavärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) för att läsa indata från. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hashalgoritm att använda. |

### Returvärde

[RSA](../../rsa/) signatur för angivna data.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) metod

Beräknar signaturen för det angivna indatavärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Ström för att läsa data som signeras från. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hashalgoritm att använda. |

### Returvärde

[RSA](../../rsa/) signatur för angivna data.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) metod

Beräknar signaturen för det angivna indatavärdet.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) för att läsa indata från. |
| offset | **int32_t** | Startindex för indatabuffertens segment. |
| count | **int32_t** | Storlek för indatabuffertens segment. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hashalgoritm att använda. |

### Returvärde

[RSA](../../rsa/) signatur för angivna data.

## Se även

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [RSACryptoServiceProvider](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)