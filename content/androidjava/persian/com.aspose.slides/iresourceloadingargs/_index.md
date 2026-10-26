---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: رابط برای آرگومان‌های بارگذاری منبع خارجی.
type: docs
url: /fa/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

رابط برای آرگومان‌های بارگذاری منبع خارجی.
## متدها

| متد | توضیح |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | Original URI of the resource as specified in imported presentation. |
| [getUri()](#getUri--) | URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI of the resource which is used for downloading if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Sets user provided data of the resource which used if [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) returns [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

URI اصلی منبع همان‌طور که در ارائه وارد شده مشخص شده است.

**بازمی‌گرداند:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```

URI منبعی که در صورت بازگشت [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) برابر [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) برای دانلود استفاده می‌شود. در ابتدا برابر URI اصلی منبع تنظیم می‌شود، اما می‌تواند به هر مقدار دیگری تغییر یابد.

**بازمی‌گرداند:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

URI منبعی که در صورت بازگشت [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) برابر [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) برای دانلود استفاده می‌شود. در ابتدا برابر URI اصلی منبع تنظیم می‌شود، اما می‌تواند به هر مقدار دیگری تغییر یابد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

داده‌های ارائه‌شده توسط کاربر برای منبع که در صورت بازگشت [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) برابر [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) استفاده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | داده‌های ارائه‌شده برای منبع byte[] |