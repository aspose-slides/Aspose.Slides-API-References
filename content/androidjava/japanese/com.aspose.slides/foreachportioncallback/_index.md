---
title: ForEach.ForEachPortionCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ja/com.aspose.slides/foreach.foreachportioncallback/
---```
public static interface ForEach.ForEachPortionCallback
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke(Portion portion, Paragraph para, BaseSlide slide, int index)](#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-) | [BaseSlide](../../com.aspose.slides/baseslide) 上の #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) の各呼び出し時に実行されるコールバックです。 |
### invoke(Portion portion, Paragraph para, BaseSlide slide, int index) {#invoke-com.aspose.slides.Portion-com.aspose.slides.Paragraph-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Portion portion, Paragraph para, BaseSlide slide, int index)
```

[BaseSlide](../../com.aspose.slides/baseslide) 上の #paragraph(Presentation,ForEachParagraphCallback).paragraph(Presentation,ForEachParagraphCallback) の各呼び出し時に実行されるコールバックです。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| portion | [Portion](../../com.aspose.slides/portion) | 現在反復中の部分 |
| para | [Paragraph](../../com.aspose.slides/paragraph) | 現在反復中の段落 |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 現在反復中のスライド |
| index | int | スライド上の現在の段落のインデックス |