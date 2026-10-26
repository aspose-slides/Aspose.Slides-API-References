---
title: ISvgShape
second_title: Aspose.Slides for Android via Java API Reference
description: SVG 모양에 대한 옵션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isvgshape/
---```
public interface ISvgShape
```

SVG 모양에 대한 옵션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [setEventHandler(int eventType, String handler)](#setEventHandler-int-java.lang.String-) | 모양에 대한 이벤트 핸들러를 설정합니다 |
| [getId()](#getId--) | 모양에 대한 ID를 설정하거나 가져옵니다 |
| [setId(String value)](#setId-java.lang.String-) | 모양에 대한 ID를 설정하거나 가져옵니다 |
### setEventHandler(int eventType, String handler) {#setEventHandler-int-java.lang.String-}
```
public abstract void setEventHandler(int eventType, String handler)
```


모양에 대한 이벤트 핸들러를 설정합니다

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| eventType | int | 이벤트 유형. |
| handler | java.lang.String | 이벤트를 처리하는 JavaScript 함수. null 값은 핸들러를 제거합니다. |

### getId() {#getId--}
```
public abstract String getId()
```


모양에 대한 ID를 설정하거나 가져옵니다

**반환:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


모양에 대한 ID를 설정하거나 가져옵니다

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  