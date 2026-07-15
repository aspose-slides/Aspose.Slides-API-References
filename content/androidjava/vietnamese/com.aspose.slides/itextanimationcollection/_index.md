---
title: ITextAnimationCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn tập hợp các hoạt ảnh văn bản.
type: docs
url: /vi/com.aspose.slides/itextanimationcollection/
---
**Tất cả các giao diện đã triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Biểu diễn tập hợp các hoạt ảnh văn bản.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về phần tử theo chỉ mục. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Trả về tất cả các phần tử |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```

Trả về phần tử theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```

Trả về tất cả các phần tử

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) phần tử. |

**Giá trị trả về:**
com.aspose.slides.ITextAnimation[] - Mảng của [ITextAnimation](../../com.aspose.slides/itextanimation)