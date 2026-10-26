---
title: IResourceLoadingArgs
second_title: Aspose.Slides for Java API Reference
description: 외부 리소스 로드 인수를 위한 인터페이스.
type: docs
url: /ko/com.aspose.slides/iresourceloadingargs/
---```
public interface IResourceLoadingArgs
```

외부 리소스 로드 인수를 위한 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOriginalUri()](#getOriginalUri--) | 가져온 프레젠테이션에 지정된 리소스의 원본 URI. |
| [getUri()](#getUri--) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 가 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) 를 반환하는 경우 다운로드에 사용되는 리소스의 URI. |
| [setUri(String value)](#setUri-java.lang.String-) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 가 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) 를 반환하는 경우 다운로드에 사용되는 리소스의 URI. |
| [setData(byte[] data)](#setData-byte---) | [IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 가 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) 를 반환하는 경우 리소스에 사용되는 사용자 제공 데이터를 설정합니다. |
### getOriginalUri() {#getOriginalUri--}
```
public abstract String getOriginalUri()
```

가져온 프레젠테이션에 지정된 리소스의 원본 URI.

**반환값:**
java.lang.String
### getUri() {#getUri--}
```
public abstract String getUri()
```

[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 가 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) 를 반환하는 경우 다운로드에 사용되는 리소스의 URI. 처음에는 리소스의 원본 URI 로 설정되지만, 언제든지 다른 값으로 재정의할 수 있습니다.

**반환값:**
java.lang.String
### setUri(String value) {#setUri-java.lang.String-}
```
public abstract void setUri(String value)
```

[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 가 [ResourceLoadingAction.Default](../../com.aspose.slides/resourceloadingaction\#Default) 를 반환하는 경우 다운로드에 사용되는 리소스의 URI. 처음에는 리소스의 원본 URI 로 설정되지만, 언제든지 다른 값으로 재정의할 수 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### setData(byte[] data) {#setData-byte---}
```
public abstract void setData(byte[] data)
```

[IResourceLoadingCallback.resourceLoading(IResourceLoadingArgs)](../../com.aspose.slides/iresourceloadingcallback\#resourceLoading-IResourceLoadingArgs-) 가 [ResourceLoadingAction.UserProvided](../../com.aspose.slides/resourceloadingaction\#UserProvided) 를 반환하는 경우 리소스에 사용되는 사용자 제공 데이터를 설정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | byte[] | 리소스에 제공된 데이터 byte[] |