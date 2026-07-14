---
title: SummaryZoomSection
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: Summary Zoom 프레임에 있는 Summary Zoom Section 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/summaryzoomsection/
---
**상속:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**구현된 모든 인터페이스:**  
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)  
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

Summary Zoom Section 객체를 Summary Zoom 프레임에 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTitle()](#getTitle--) | Summary Zoom Section 객체의 텍스트 제목을 반환합니다. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Summary Zoom Section 객체의 텍스트 제목을 반환합니다. |
| [getDescription()](#getDescription--) | Summary Zoom Section 객체의 텍스트 설명을 반환합니다. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Summary Zoom Section 객체의 텍스트 설명을 반환합니다. |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Summary Zoom Section 객체의 텍스트 제목을 반환합니다.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**반환값:**  
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Summary Zoom Section 객체의 텍스트 제목을 반환합니다.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```

Summary Zoom Section 객체의 텍스트 설명을 반환합니다.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**반환값:**  
java.lang.String

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```

Summary Zoom Section 객체의 텍스트 설명을 반환합니다.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |