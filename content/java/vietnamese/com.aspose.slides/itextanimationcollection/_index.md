---
title: ITextAnimationCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho bộ sưu tập các hoạt ảnh văn bản.
type: docs
url: /vi/com.aspose.slides/itextanimationcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Đại diện cho bộ sưu tập các hoạt ảnh văn bản.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về phần tử theo chỉ số. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Trả về tất cả các phần tử |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Trả về phần tử theo chỉ số.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
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

**Trả về:**
com.aspose.slides.ITextAnimation[] - Mảng của [ITextAnimation](../../com.aspose.slides/itextanimation)