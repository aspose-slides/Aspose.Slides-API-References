---
title: IResourceLoadingArgs
second_title: Aspose.Slides для Java справочник API
description: Интерфейс аргументов загрузки внешних ресурсов.
type: docs
url: /ru/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Интерфейс аргументов загрузки внешних ресурсов.
## Методы

| Метод | Описание |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Исходный URI ресурса, указанный в импортированной презентации. |
| [getUri()](#getUri--) | URI ресурса, используемый для загрузки, если [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) возвращает [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI ресурса, используемый для загрузки, если [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) возвращает [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Устанавливает пользовательские данные ресурса, которые используются, если [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) возвращает [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


Исходный URI ресурса, указанный в импортированной презентации.

**Возвращает:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI ресурса, используемый для загрузки, если [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) возвращает [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Изначально он установлен в исходный URI ресурса, но может быть переопределён любым значением.

**Возвращает:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI ресурса, используемый для загрузки, если [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) возвращает [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Изначально он установлен в исходный URI ресурса, но может быть переопределён любым значением.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Устанавливает пользовательские данные ресурса, которые используются, если [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) возвращает [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | byte[] | Предоставленные данные ресурса byte[] |