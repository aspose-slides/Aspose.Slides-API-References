---
title: Seek()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает позицию потока, представленного текущим объектом.
type: docs
weight: 365
url: /ru/system.net.security/sslstream/seek/
---
## SslStream::Seek(int64_t, IO::SeekOrigin) метод


Устанавливает позицию потока, представленного текущим объектом.

```cpp
int64_t System::Net::Security::SslStream::Seek(int64_t offset, IO::SeekOrigin origin) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| offset | **int64_t** | Смещение в байтах относительно позиции, указанной **origin** |
| origin | [IO::SeekOrigin](../../../system.io/seekorigin/) | Указывает позицию, от которой и направление, в котором вычисляется смещение |

### Возвращаемое значение

Новая позиция потока

## См. также

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)