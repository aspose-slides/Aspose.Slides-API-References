---
title: IsBypassed()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает значение, указывающее, следует ли не использовать прокси для указанного узла.
type: docs
weight: 40
url: /ru/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) метод


Возвращает значение, указывающее, следует ли не использовать прокси для указанного узла.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI узла для проверки. |

### Возвращаемое значение

True, если прокси-сервер не должен использоваться, иначе false.

## См. также

* Типообъявление [SharedPtr](../../../system/sharedptr/)
* Класс [Uri](../../../system/uri/)
* Класс [IWebProxy](../)
* Пространство имён [System::Net](../../)
* Библиотека [Aspose.Slides](../../../)