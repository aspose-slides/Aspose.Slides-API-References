---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /ru/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Интерфейс для аргументов загрузки внешних ресурсов.
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

**Возвращаемое значение:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI ресурса, используемый для загрузки, если [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) возвращает [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Изначально он установлен как исходный URI ресурса, но может быть переопределён на любое значение.

**Возвращаемое значение:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI ресурса, используемый для загрузки, если [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) возвращает [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Изначально он установлен как исходный URI ресурса, но может быть переопределён на любое значение.

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