---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 경고를 받는 클래스용 인터페이스
type: docs
url: /ko/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

경고를 받는 클래스용 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | 경고를 받고 작업을 중단해야 하는지를 결정하는 콜백 메서드. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

경고를 받고 작업을 중단해야 하는지를 결정하는 콜백 메서드.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | 처리할 경고. |

**반환값:**
int - 중단 결정 [ReturnAction](../../com.aspose.slides/returnaction).