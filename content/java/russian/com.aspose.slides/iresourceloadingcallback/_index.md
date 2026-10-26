---
title: IResourceLoadingCallback
second_title: Aspose.Slides для Java справочник API
description: Интерфейс обратного вызова, используемый для управления загрузкой внешних ресурсов.
type: docs
url: /ru/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

Интерфейс обратного вызова, используемый для управления загрузкой внешних ресурсов.
## Методы

| Метод | Описание |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | Метод обратного вызова, регулирующий загрузку внешних ресурсов. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```

Метод обратного вызова, регулирующий загрузку внешних ресурсов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | Данные загружаемого ресурса [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**Возвращаемое значение:**
int - Решение о загрузке ресурса [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).