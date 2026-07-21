---
title: VerifyData()
second_title: Aspose.Slides для C++: справочник API
description: Проверяет подпись данных.
type: docs
weight: 209
url: /ru/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) method


Проверяет подпись данных.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) to check signature for. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Hash algorithm to use. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | Signature as received. |

### Возвращаемое значение

True если подпись действительна, false в противном случае.

## См. также

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)