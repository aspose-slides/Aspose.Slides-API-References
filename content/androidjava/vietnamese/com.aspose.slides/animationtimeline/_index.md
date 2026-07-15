---
title: AnimationTimeLine
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho dòng thời gian của hoạt ảnh.
type: docs
url: /vi/com.aspose.slides/animationtimeline/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
```
public class AnimationTimeLine extends DomObject<BaseSlide> implements IAnimationTimeLine
```

Đại diện cho dòng thời gian của hoạt ảnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Trả về bộ sưu tập các chuỗi tương tác. |
| [getMainSequence()](#getMainSequence--) | Trả về chuỗi chính, có thể chỉ chứa bộ sưu tập các hiệu ứng chính. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Trả về bộ sưu tập các hoạt ảnh văn bản. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public final ISequenceCollection getInteractiveSequences()
```


Trả về bộ sưu tập các chuỗi tương tác. Các chuỗi này có thể chỉ chứa các hiệu ứng bằng \"click on shape\" với hình dạng mục tiêu được chỉ định. Chỉ đọc [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Trả về:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public final ISequence getMainSequence()
```


Trả về chuỗi chính, có thể chỉ chứa bộ sưu tập các hiệu ứng chính. Chỉ đọc [ISequence](../../com.aspose.slides/isequence).

**Trả về:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public final ITextAnimationCollection getTextAnimationCollection()
```


Trả về bộ sưu tập các hoạt ảnh văn bản. Chỉ đọc [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Trả về:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)