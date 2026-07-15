---
title: PVIObject
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Bọc hạ tầng dịch vụ cơ bản cho các đối tượng có thể là chủ đề của việc kế thừa giá trị thuộc tính.
type: docs
url: /vi/com.aspose.slides/pviobject/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Bọc hạ tầng dịch vụ cơ bản cho các đối tượng có thể là chủ đề của việc kế thừa giá trị thuộc tính.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | So sánh với đối tượng được chỉ định. |
| [hashCode()](#hashCode--) | Trả về mã băm. |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Trả về IPresentationComponent cha. Chỉ đọc [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Trả về:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**Trả về:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Trả về slide cơ sở. Chỉ đọc [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Trả về:**
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Trả về bản trình chiếu. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[Presentation](../../com.aspose.slides/presentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

So sánh với đối tượng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng để so sánh. |

**Trả về:**
boolean - True nếu các đối tượng bằng nhau, ngược lại false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Trả về mã băm.

**Trả về:**
int - Mã băm.