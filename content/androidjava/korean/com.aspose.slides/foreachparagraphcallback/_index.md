---
title: ForEach.ForEachParagraphCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ko/com.aspose.slides/foreach.foreachparagraphcallback/
---```
public static interface ForEach.ForEachParagraphCallback
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | 각 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 에 대해 호출되는 콜백은 [BaseSlide](../../com.aspose.slides/baseslide)에 있습니다. |
### invoke(Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Paragraph para, BaseSlide slide, int index)
```

각 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 에 대해 호출되는 콜백은 [BaseSlide](../../com.aspose.slides/baseslide)에 있습니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) | 현재 반복 중인 단락 |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 현재 반복 중인 슬라이드 |
| index | int | 슬라이드에서 현재 단락의 인덱스 |