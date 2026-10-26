---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Android via Java API Reference
description: Interface for external resource loading arguments.
type: docs
url: /ko/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

외부 리소스 로드 인수에 대한 인터페이스입니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | 가져온 프레젠테이션에 지정된 리소스의 원본 URI입니다. |
| [getUri()](#getUri--) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-)가 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)를 반환하는 경우 다운로드에 사용되는 리소스의 URI입니다. |
| [setUri(String value)](#setUri-java.lang.String-) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-)가 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)를 반환하는 경우 다운로드에 사용되는 리소스의 URI입니다. |
| [setData(byte[] data)](#setData-byte---) | 사용자가 제공한 데이터가 [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-)가 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided)를 반환하는 경우에 사용되는 리소스의 데이터를 설정합니다. |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```


가져온 프레젠테이션에 지정된 리소스의 원본 URI입니다.

**반환값:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```


[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-)가 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)를 반환하는 경우 다운로드에 사용되는 리소스의 URI입니다. 초기값은 리소스의 원본 URI로 설정되지만, 언제든지 다른 값으로 재정의할 수 있습니다.

**반환값:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```


[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-)가 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default)를 반환하는 경우 다운로드에 사용되는 리소스의 URI입니다. 초기값은 리소스의 원본 URI로 설정되지만, 언제든지 다른 값으로 재정의할 수 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```


[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-)가 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided)를 반환하는 경우에 사용되는 리소스의 데이터를 사용자가 제공한 데이터로 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | byte[] | 리소스에 제공된 데이터 byte[] |