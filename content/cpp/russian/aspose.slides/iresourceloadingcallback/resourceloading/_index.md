---
title: ResourceLoading()
second_title: Aspose.Slides для справки API C++
description: Метод-обратного вызова, который регулирует загрузку внешних ресурсов.
type: docs
weight: 1
url: /ru/aspose.slides/iresourceloadingcallback/resourceloading/
---
## IResourceLoadingCallback::ResourceLoading(System::SharedPtr\<IResourceLoadingArgs\>) method

Метод-обратного вызова, который регулирует загрузку внешних ресурсов.

```cpp
virtual ResourceLoadingAction Aspose::Slides::IResourceLoadingCallback::ResourceLoading(System::SharedPtr<IResourceLoadingArgs> args)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | [System::SharedPtr](../../../system/sharedptr/)\<[IResourceLoadingArgs](../../iresourceloadingargs/)\> | Данные загружаемого ресурса [IResourceLoadingArgs](../../iresourceloadingargs/). |

### Возвращаемое значение

Решение о загрузке ресурса [ResourceLoadingAction](../../resourceloadingaction/).

## См. также

* Перечисление [ResourceLoadingAction](../../resourceloadingaction/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IResourceLoadingArgs](../../iresourceloadingargs/)
* Класс [IResourceLoadingCallback](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)