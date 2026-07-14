---
title: ISummaryZoomSection
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Summary Zoom 프레임에서 Summary Zoom Section 객체를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isummaryzoomsection/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Summary Zoom 프레임에서 Summary Zoom Section 객체를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getTitle()](#getTitle--) | Summary Zoom Section 객체의 텍스트 제목을 반환합니다. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Summary Zoom Section 객체의 텍스트 제목을 반환합니다. |
| [getDescription()](#getDescription--) | Summary Zoom Section 객체의 텍스트 설명을 반환합니다. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Summary Zoom Section 객체의 텍스트 설명을 반환합니다. |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Summary Zoom Section 객체의 텍스트 제목을 반환합니다.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**반환값:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```


Summary Zoom Section 객체의 텍스트 제목을 반환합니다.

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
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
public abstract void setDescription(String value)
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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |