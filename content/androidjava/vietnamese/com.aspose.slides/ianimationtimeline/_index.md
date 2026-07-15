---
title: IAnimationTimeLine
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn dòng thời gian của hoạt ảnh.
type: docs
url: /vi/com.aspose.slides/ianimationtimeline/
---```
public interface IAnimationTimeLine
```

Biểu diễn dòng thời gian của hoạt ảnh.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInteractiveSequences()](#getInteractiveSequences--) | Trả về bộ sưu tập các chuỗi tương tác. |
| [getMainSequence()](#getMainSequence--) | Trả về chuỗi chính có thể chỉ chứa bộ sưu tập hiệu ứng chính. |
| [getTextAnimationCollection()](#getTextAnimationCollection--) | Trả về bộ sưu tập các hoạt ảnh văn bản. |
### getInteractiveSequences() {#getInteractiveSequences--}
```
public abstract ISequenceCollection getInteractiveSequences()
```

Trả về bộ sưu tập các chuỗi tương tác. Các chuỗi này có thể chỉ chứa các hiệu ứng bằng "click on shape" với hình dạng mục tiêu được chỉ định. Chỉ đọc [ISequenceCollection](../../com.aspose.slides/isequencecollection).

**Trả về:**  
[ISequenceCollection](../../com.aspose.slides/isequencecollection)
### getMainSequence() {#getMainSequence--}
```
public abstract ISequence getMainSequence()
```

Trả về chuỗi chính có thể chỉ chứa bộ sưu tập hiệu ứng chính. Chỉ đọc [ISequence](../../com.aspose.slides/isequence).

**Trả về:**  
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimationCollection() {#getTextAnimationCollection--}
```
public abstract ITextAnimationCollection getTextAnimationCollection()
```

Trả về bộ sưu tập các hoạt ảnh văn bản. Chỉ đọc [ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection).

**Trả về:**  
[ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)