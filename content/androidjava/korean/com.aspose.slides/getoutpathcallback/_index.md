---
title: Convert.GetOutPathCallback
second_title: Aspose.Slides for Android via Java API Reference
description: 
type: docs
url: /ko/com.aspose.slides/convert.getoutpathcallback/
---```
public static interface Convert.GetOutPathCallback
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(Slide slide, int index)](#invoke-com.aspose.slides.Slide-int-) | 각 [Slide](../../com.aspose.slides/slide)에 대해 호출되는 콜백이며, 반환될 출력 경로가 예상됩니다. |
### invoke(Slide slide, int index) {#invoke-com.aspose.slides.Slide-int-}
```
public abstract String invoke(Slide slide, int index)
```


각 [Slide](../../com.aspose.slides/slide)에 대해 호출되는 콜백이며, 반환될 출력 경로가 예상됩니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slide | [Slide](../../com.aspose.slides/slide) | 현재 반복된 슬라이드 |
| index | int | 현재 슬라이드의 인덱스 |

**반환값:**
java.lang.String