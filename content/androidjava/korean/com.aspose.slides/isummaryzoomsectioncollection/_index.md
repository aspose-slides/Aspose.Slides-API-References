---
title: ISummaryZoomSectionCollection
second_title: Java API 레퍼런스를 통해 Android용 Aspose.Slides
description: Summary Zoom Section 객체의 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/isummaryzoomsectioncollection/
---
**구현된 모든 인터페이스:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Summary Zoom Section 객체의 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 지정된 인덱스의 요소를 가져옵니다. |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | 새 Summary Zoom Section 객체를 생성하고 컬렉션에 추가합니다 |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | 지정된 섹션에 대한 Summary Zoom Section 요소를 반환합니다. |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | 컬렉션에서 Summary Zoom Section 객체를 제거합니다. |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | 지정된 SummaryZoomSection 객체의 인덱스를 반환합니다. |
| [clear()](#clear--) | 컬렉션에서 모든 SummaryZoomSection 객체를 제거합니다. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

지정된 인덱스의 요소를 가져옵니다. 읽기 전용 [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | int |  |

**반환값:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

새 Summary Zoom Section 객체를 생성하고 컬렉션에 추가합니다.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 새 Summary Zoom Section 요소에 대한 Section [ISection](../../com.aspose.slides/isection) |

해당 section에 대한 요소가 컬렉션에 이미 존재하는 경우, 기존 요소가 반환됩니다.

**반환값:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - 추가된 [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) 요소
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

주어진 section에 대한 Summary Zoom Section 요소를 반환합니다.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 찾을 Section [ISection](../../com.aspose.slides/isection) |

**반환값:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) 또는 컬렉션에 해당 section에 대한 요소가 없을 경우 null.
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

컬렉션에서 Summary Zoom Section 객체를 제거합니다.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | 제거될 Summary Zoom Section 요소에 대한 Section [ISection](../../com.aspose.slides/isection). |

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

지정된 SummaryZoomSection 객체의 인덱스를 반환합니다.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | 찾을 SummaryZoomSection 객체 [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection). |

**반환값:**
int - SummaryZoomSection 객체의 인덱스 또는 해당 컬렉션에 속하지 않은 경우 -1.
### clear() {#clear--}
```
public abstract void clear()
```

컬렉션에서 모든 SummaryZoomSection 객체를 제거합니다.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```