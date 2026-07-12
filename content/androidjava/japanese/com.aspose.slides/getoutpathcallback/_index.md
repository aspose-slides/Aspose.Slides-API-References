---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ja/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | 各[Slide](../../com.aspose.slides/slide)に対して呼び出されるコールバックで、出力パスが返されることが期待されます。 |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```

各[Slide](../../com.aspose.slides/slide)に対して呼び出されるコールバックで、出力パスが返されることが期待されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | 現在反復中のスライド |
| index | int | 現在のスライドのインデックス |

**戻り値:**
java.lang.String