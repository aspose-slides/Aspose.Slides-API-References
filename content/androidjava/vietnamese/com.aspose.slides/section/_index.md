---
title: Section
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn phần của các slide.
type: docs
url: /vi/com.aspose.slides/section/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Biểu diễn một phần của slide.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getName()](#getName--) | Tên của phần. |
| [setName(String value)](#setName-java.lang.String-) | Tên của phần. |
| [getSectionId()](#getSectionId--) | Id của phần. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Trả về slide đầu tiên của phần. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Trả về danh sách các slide trong phần. |
### getName() {#getName--}
```
public final String getName()
```

Tên của phần.

**Trả về:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Tên của phần.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```

Id của phần.

**Trả về:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

Trả về slide đầu tiên của phần.

**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

Trả về danh sách các slide trong phần.

**Trả về:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Danh sách các slide.