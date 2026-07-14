---
title: IAutoShape
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: AutoShape를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iautoshape/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

AutoShape를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | AutoShape의 잠금을 반환합니다. |
| [getTextFrame()](#getTextFrame--) | AutoShape에 대한 TextFrame 객체를 반환합니다. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | 이 자동 모양을 스타일이나 채우기 형식에 의해 지정된 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | 이 자동 모양을 스타일이나 채우기 형식에 의해 지정된 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | 도형에 새 TextFrame을 추가합니다. |
| [isTextBox()](#isTextBox--) | 도형이 텍스트 상자인지 지정합니다. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

AutoShape의 잠금을 반환합니다. 읽기 전용 [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**반환:**  
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

AutoShape에 대한 TextFrame 객체를 반환합니다. 읽기 전용 [ITextFrame](../../com.aspose.slides/itextframe).

**반환:**  
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

이 자동 모양을 스타일이나 채우기 형식에 의해 지정된 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**반환:**  
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

이 자동 모양을 스타일이나 채우기 형식에 의해 지정된 대신 슬라이드의 배경 채우기로 채워야 하는지 여부를 결정합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

도형에 새 TextFrame을 추가합니다. 도형에 이미 TextFrame이 있는 경우 텍스트만 변경합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| text | java.lang.String | 새 TextFrame의 기본 텍스트. |

**반환:**
[ITextFrame](../../com.aspose.slides/itextframe) - 새 [ITextFrame](../../com.aspose.slides/itextframe) 객체.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

도형이 텍스트 상자인지 지정합니다.

--------------------

도형이 텍스트 상자로 지정되지 않았다고 해서 텍스트를 첨부할 수 없다는 의미는 아닙니다. 텍스트 상자는 단지 특정 속성을 가진 특수화된 도형일 뿐입니다.

**반환:**  
boolean