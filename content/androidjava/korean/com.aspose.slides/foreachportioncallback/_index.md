---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ko/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | 각 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 에 대해 [BaseSlide](../../com.aspose.slides/baseslide)에서 호출되는 콜백입니다. |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```


각 \#paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) 에 대해 [BaseSlide](../../com.aspose.slides/baseslide)에서 호출되는 콜백입니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | 현재 반복된 portion |
| para | [Paragraph](../../com.aspose.slides/paragraph) | 현재 반복된 paragraph |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 현재 반복된 slide |
| index | int | 슬라이드에 있는 현재 paragraph의 인덱스 |