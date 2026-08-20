---
title: IAnimationTimeLine
second_title: Aspose.Slides for Java API Reference
description: Represents timeline of animation.
type: docs
url: /vi/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Biểu diễn dòng thời gian của hoạt ảnh.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Trả về tập hợp các chuỗi tương tác. |
| [getMainSequence()](#getMainSequence--) | Trả về chuỗi chính có thể chứa chỉ bộ sưu tập hiệu ứng chính. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Trả về tập hợp các hoạt ảnh văn bản. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```


Trả về tập hợp các chuỗi tương tác. Các chuỗi này có thể chứa chỉ các hiệu ứng bằng “nhấp vào hình” với hình mục tiêu được chỉ định. Chỉ đọc [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Trả về:**
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```


Trả về chuỗi chính có thể chứa chỉ bộ sưu tập hiệu ứng chính. Chỉ đọc [ISequence](../../com.aspose.slides/isequence).

**Trả về:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```


Trả về tập hợp các hoạt ảnh văn bản. Chỉ đọc [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Trả về:**
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)