---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /ja/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## メソッド

| Method | Description |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | 各 #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) が [BaseSlide](../../com.aspose.slides/baseslide) 上で呼び出されるコールバックです。 |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

各 #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) が [BaseSlide](../../com.aspose.slides/baseslide) 上で呼び出されるコールバックです。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | 現在反復中の portion |
| para | [Paragraph](../../com.aspose.slides/paragraph) | 現在反復中の paragraph |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 現在反復中の slide |
| index | int | スライド上の現在の paragraph のインデックス |