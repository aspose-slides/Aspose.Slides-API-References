---
title: IWarningInfo
second_title: Aspose.Slides for Java API Reference
description: 모든 경고에 대한 기본 인터페이스를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

모든 경고에 대한 기본 인터페이스를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | If receiver is not null ends warning to a specified receiver and throws the AbortRequestedException if receiver decided to abort a operation. |
| [getWarningType()](#getWarningType--) | Returns a type of warning. |
| [getDescription()](#getDescription--) | Returns a human readable description of this warning. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```


receiver가 null이 아닌 경우 지정된 수신자에게 경고를 종료하고, 수신자가 작업 중단을 결정한 경우 AbortRequestedException을 발생시킵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Receiver object [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

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