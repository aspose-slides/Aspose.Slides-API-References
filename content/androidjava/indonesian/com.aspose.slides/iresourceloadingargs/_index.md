---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Antarmuka untuk argumen pemuatan sumber daya eksternal.
type: docs
url: /id/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

Antarmuka untuk argumen pemuatan sumber daya eksternal.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | URI asli sumber daya seperti yang ditentukan dalam presentasi yang diimpor. |
| [getUri()](#getUri--) | URI sumber daya yang digunakan untuk mengunduh jika [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) mengembalikan [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setUri(String value)](#setUri-java.lang.String-) | URI sumber daya yang digunakan untuk mengunduh jika [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) mengembalikan [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). |
| [setData(byte[] data)](#setData-byte---) | Mengatur data yang disediakan pengguna untuk sumber daya yang digunakan jika [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) mengembalikan [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided). |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


URI asli sumber daya seperti yang ditentukan dalam presentasi yang diimpor.

**Mengembalikan:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


URI sumber daya yang digunakan untuk mengunduh jika [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) mengembalikan [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Awalnya diatur ke URI asli sumber daya, tetapi dapat didefinisikan ulang ke nilai apa pun.

**Mengembalikan:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


URI sumber daya yang digunakan untuk mengunduh jika [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) mengembalikan [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default). Awalnya diatur ke URI asli sumber daya, tetapi dapat didefinisikan ulang ke nilai apa pun.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


Mengatur data yang disediakan pengguna untuk sumber daya yang digunakan jika [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) mengembalikan [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data yang disediakan untuk sumber daya byte[] |