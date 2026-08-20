---
title: BaseHandoutNotesSlideHeaderFooterManager
second_title: Aspose.Slides Java API 레퍼런스
description: 모든 유형의 유인물 및 노트 슬라이드에 대한 헤더 자리 표시자를 포함한 자리 표시자의 동작을 관리하는 매니저를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/basehandoutnotesslideheaderfootermanager/
---
**Inheritance:**  
상속:
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**All Implemented Interfaces:**  
구현된 모든 인터페이스:
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public abstract class BaseHandoutNotesSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements IBaseHandoutNotesSlideHeaderFooterManag
```

모든 유형의 유인물 및 노트 슬라이드에 대한 헤더 자리 표시자를 포함한 자리 표시자 동작을 관리하는 매니저를 나타냅니다.

## Methods
## 메서드

| Method | Description |
| --- | --- |
| 메서드 | 설명 |
| [isHeaderVisible()](#isHeaderVisible--) | 헤더 자리 표시자가 존재함을 나타내는 값을 가져옵니다. |
| [setHeaderVisibility(boolean isVisible)](#setHeaderVisibility-boolean-) | 슬라이드 헤더 자리 표시자의 가시성을 변경합니다. |
| [setHeaderText(String text)](#setHeaderText-java.lang.String-) | 슬라이드 헤더 자리 표시자에 텍스트를 설정합니다. |

### isHeaderVisible() {#isHeaderVisible--}
```
public final boolean isHeaderVisible()
```

헤더 자리 표시자가 존재함을 나타내는 값을 가져옵니다. 읽기 전용 boolean.

**Returns:**  
**반환:**  
boolean

### setHeaderVisibility(boolean isVisible) {#setHeaderVisibility-boolean-}
```
public final void setHeaderVisibility(boolean isVisible)
```

슬라이드 헤더 자리 표시자의 가시성을 변경합니다.

**Parameters:**  
**매개변수:**

| Parameter | Type | Description |
| --- | --- | --- |
| Parameter | Type | Description |
| isVisible | boolean | true - 헤더 자리 표시자를 표시하고, 그렇지 않으면 숨깁니다. |

### setHeaderText(String text) {#setHeaderText-java.lang.String-}
```
public final void setHeaderText(String text)
```

슬라이드 헤더 자리 표시자에 텍스트를 설정합니다.

**Parameters:**  
**매개변수:**

| Parameter | Type | Description |
| --- | --- | --- |
| Parameter | Type | Description |
| text | java.lang.String | 설정할 텍스트. |