---
title: ResourceLoadingAction
second_title: Aspose.Slides для C++ справки API
description: Определяет режим загрузки внешних ресурсов.
type: docs
weight: 6761
url: /ru/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction перечисление

Определяет режим загрузки внешних ресурсов.

```cpp
enum class ResourceLoadingAction
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../) будет загружать внешний ресурс как обычно. |
| Skip | 1 | [Aspose.Slides](../) пропустит загрузку внешнего ресурса. Только ссылка без данных будет сохранена для изображения. |
| UserProvided | 2 | [Aspose.Slides](../) будет использовать массив байтов, предоставленный пользователем в [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/) в качестве данных изображения. |

## См. также

* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)