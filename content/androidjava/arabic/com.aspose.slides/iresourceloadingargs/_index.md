---
title: IResourceLoadingArgs
second_title: Aspose.Slides لنظام Android عبر Java API Reference
description: واجهة لوسائط تحميل الموارد الخارجية.
type: docs
url: /ar/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

واجهة لوسائط تحميل الموارد الخارجية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | URI الأصلي للموارد كما هو محدد في العرض التقديمي المستورد. |
| [getUri()](#getUri--) | URI للموارد الذي يُستخدم للتنزيل إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI للموارد الذي يُستخدم للتنزيل إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | يضبط البيانات التي يوفرها المستخدم للموارد والتي تُستخدم إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


URI الأصلي للموارد كما هو محدد في العرض التقديمي المستورد.

**القيمة المرجعة:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI للموارد الذي يُستخدم للتنزيل إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). في البداية يتم تعيينه إلى URI الأصلي للموارد، ولكن يمكن إعادة تعريفه إلى أي قيمة.

**القيمة المرجعة:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI للموارد الذي يُستخدم للتنزيل إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). في البداية يتم تعيينه إلى URI الأصلي للموارد، ولكن يمكن إعادة تعريفه إلى أي قيمة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


يضبط البيانات التي يوفرها المستخدم للموارد والتي تُستخدم إذا كان [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) يُعيد [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] | البيانات المقدمة للمورد byte[] |