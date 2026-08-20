---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /ar/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

واجهة لتحميل الموارد الخارجية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | URI الأصلي للموارد كما هو محدد في العرض المستورد. |
| [getUri()](#getUri--) | URI للموارد المستخدمة في التنزيل إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI للموارد المستخدمة في التنزيل إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | يحدد البيانات التي يوفرها المستخدم للموارد والتي تُستخدم إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


URI الأصلي للموارد كما هو محدد في العرض المستورد.

**Returns:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI للموارد المستخدمة في التنزيل إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). في البداية يتم تعيينه إلى URI الأصلي للموارد، ولكنه يمكن إعادة تعريفه إلى أي قيمة.

**Returns:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI للموارد المستخدمة في التنزيل إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). في البداية يتم تعيينه إلى URI الأصلي للموارد، ولكنه يمكن إعادة تعريفه إلى أي قيمة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


يحدد البيانات التي يوفرها المستخدم للموارد والتي تُستخدم إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | byte[] | البيانات المقدمة للموارد byte[] |