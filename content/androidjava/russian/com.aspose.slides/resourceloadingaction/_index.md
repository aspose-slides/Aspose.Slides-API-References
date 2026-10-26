---
title: ResourceLoadingAction
second_title: Aspose.Slides для Android через справочник Java API
description: Указывает режим загрузки внешних ресурсов.
type: docs
url: /ru/com.aspose.slides/resourceloadingaction/
---
**Наследование:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

Указывает режим загрузки внешних ресурсов.
## Поля

| Поле | Описание |
| --- | --- |
| [Default](#Default) | Aspose.Slides будет загружать внешний ресурс как обычно. |
| [Skip](#Skip) | Aspose.Slides пропустит загрузку внешнего ресурса. |
| [UserProvided](#UserProvided) | Aspose.Slides будет использовать массив байтов, предоставленный пользователем в [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) в качестве данных изображения. |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides будет загружать внешний ресурс как обычно.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides пропустит загрузку внешнего ресурса. Только ссылка без данных будет сохранена для изображения.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides будет использовать массив байтов, предоставленный пользователем в [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---) в качестве данных изображения.