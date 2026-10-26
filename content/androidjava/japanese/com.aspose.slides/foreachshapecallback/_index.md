---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ja/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## メソッド

| Method | Description |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | [Presentation](../../com.aspose.slides/presentation) の各 [Shape](../../com.aspose.slides/shape) に対して呼び出されるコールバックです。 |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


[Presentation](../../com.aspose.slides/presentation) の各 [Shape](../../com.aspose.slides/shape) に対して呼び出されるコールバックです。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | 現在イテレート中のシェイプ |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 現在イテレート中のスライド |
| index | int | 現在のレイアウトスライドのインデックス |