---
title: IResourceLoadingCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to manage external resources loading.
type: docs
url: /ko/com.aspose.slides/iresourceloadingcallback/
---```
public interface IResourceLoadingCallback
```

외부 리소스 로드를 관리하는 데 사용되는 콜백 인터페이스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [resourceLoading(IResourceLoadingArgs args)](#resourceLoading-com.aspose.slides.IResourceLoadingArgs-) | 외부 리소스 로드를 제어하는 콜백 메서드. |
### resourceLoading(IResourceLoadingArgs args) {#resourceLoading-com.aspose.slides.IResourceLoadingArgs-}
```
public abstract int resourceLoading(IResourceLoadingArgs args)
```


외부 리소스 로드를 제어하는 콜백 메서드.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| args | [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs) | 로드 중인 리소스 데이터 [IResourceLoadingArgs](../../com.aspose.slides/iresourceloadingargs). |

**반환값:**
int - 리소스 로드 결정 [ResourceLoadingAction](../../com.aspose.slides/resourceloadingaction).