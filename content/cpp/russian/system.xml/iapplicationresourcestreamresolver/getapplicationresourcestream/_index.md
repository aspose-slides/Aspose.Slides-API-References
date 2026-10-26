---
title: GetApplicationResourceStream()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает поток ресурса приложения, указанный в заданном URI.
type: docs
weight: 1
url: /ru/system.xml/iapplicationresourcestreamresolver/getapplicationresourcestream/
---
## IApplicationResourceStreamResolver::GetApplicationResourceStream(SharedPtr\<Uri\>) метод


Возвращает поток ресурса приложения, указанный в заданном URI.

```cpp
virtual SharedPtr<IO::Stream> System::Xml::IApplicationResourceStreamResolver::GetApplicationResourceStream(SharedPtr<Uri> relativeUri)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| relativeUri | [SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Относительный URI. |

### Возвращаемое значение

Поток ресурса приложения.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [Uri](../../../system/uri/)
* Class [IApplicationResourceStreamResolver](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)