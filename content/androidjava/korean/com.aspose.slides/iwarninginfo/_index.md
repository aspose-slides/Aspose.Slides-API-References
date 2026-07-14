---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /ko/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

모든 경고에 대한 기본 인터페이스를 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | receiver가 null이 아니면 지정된 receiver에 경고를 종료하고, receiver가 작업을 중단하기로 결정한 경우 AbortRequestedException을 발생시킵니다. |
| [getWarningType()](#getWarningType--) | 경고 유형을 반환합니다. |
| [getDescription()](#getDescription--) | 이 경고에 대한 사람이 읽을 수 있는 설명을 반환합니다. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

receiver가 null이 아니면 지정된 receiver에 경고를 종료하고, receiver가 작업을 중단하기로 결정한 경우 AbortRequestedException을 발생시킵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | 수신기 객체 [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

경고 유형을 반환합니다. 읽기 전용 [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**반환값:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

이 경고에 대한 사람이 읽을 수 있는 설명을 반환합니다. 읽기 전용 String.

**반환값:**
java.lang.String