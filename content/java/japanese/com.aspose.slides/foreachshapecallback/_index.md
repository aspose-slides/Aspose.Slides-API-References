---
title: ForEach.ForEachShapeCallback
second_title: Aspose.Slides for Java API Reference
description: 
type: docs
url: /ja/com.aspose.slides/foreach.foreachshapecallback/
---```
public static interface ForEach.ForEachShapeCallback
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke(Shape shape, BaseSlide slide, int index)](#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-) | [Presentation](../../com.aspose.slides/presentation)内の各[Shape](../../com.aspose.slides/shape)に対して呼び出されるコールバック。 |
### invoke(Shape shape, BaseSlide slide, int index) {#invoke-com.aspose.slides.Shape-com.aspose.slides.BaseSlide-int-}
```
public abstract void invoke(Shape shape, BaseSlide slide, int index)
```


[Presentation](../../com.aspose.slides/presentation)内の各[Shape](../../com.aspose.slides/shape)に対して呼び出されるコールバック。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.slides/shape) | 現在反復されているシェイプ |
| slide | [BaseSlide](../../com.aspose.slides/baseslide) | 現在反復されているスライド |
| index | int | 現在のレイアウトスライドのインデックス |