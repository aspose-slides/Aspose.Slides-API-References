---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface for classes which receive warning
type: docs
url: /ko/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

경고를 받는 클래스용 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | 경고를 수신하고 작업 중단 여부를 결정하는 콜백 메서드. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

경고를 수신하고 작업 중단 여부를 결정하는 콜백 메서드.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | 처리할 경고. |

**반환값:**
int - 작업 중단 결정 [ReturnAction](../../com.aspose.slides/returnaction).