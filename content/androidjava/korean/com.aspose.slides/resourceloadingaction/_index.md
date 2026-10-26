---
title: ResourceLoadingAction
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 외부 리소스 로드 모드를 지정합니다.
type: docs
url: /ko/com.aspose.slides/resourceloadingaction/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ResourceLoadingAction extends System.Enum
```

외부 리소스 로드 모드를 지정합니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [Default](#Default) | Aspose.Slides는 외부 리소스를 일반적으로 로드합니다. |
| [Skip](#Skip) | Aspose.Slides는 외부 리소스 로드를 건너뜁니다. |
| [UserProvided](#UserProvided) | Aspose.Slides는 사용자가 [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---)에서 제공한 바이트 배열을 이미지 데이터로 사용합니다. |
### Default {#Default}
```
public static final int Default
```

Aspose.Slides는 외부 리소스를 일반적으로 로드합니다.

### Skip {#Skip}
```
public static final int Skip
```

Aspose.Slides는 외부 리소스 로드를 건너뜁니다. 데이터가 없는 링크만 이미지에 저장됩니다.

### UserProvided {#UserProvided}
```
public static final int UserProvided
```

Aspose.Slides는 사용자가 [IResourceLoadingArgs.setData(byte[])](../../com.aspose.slides/iresourceloadingargs\#setData-byte---)에서 제공한 바이트 배열을 이미지 데이터로 사용합니다.