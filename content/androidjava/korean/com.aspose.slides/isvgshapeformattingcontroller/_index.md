---
title: ISvgShapeFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: SVG 모양 생성을 제어합니다.
type: docs
url: /ko/com.aspose.slides/isvgshapeformattingcontroller/
---```
public interface ISvgShapeFormattingController
```

SVG 모양 생성을 제어합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) | 이 함수는 SVG로 모양을 렌더링하기 전에 호출되어 사용자가 결과 SVG를 제어할 수 있도록 합니다. |
### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public abstract void formatShape(ISvgShape svgShape, IShape shape)
```


이 함수는 SVG로 모양을 렌더링하기 전에 호출되어 사용자가 결과 SVG를 제어할 수 있도록 합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) | SVG 모양 생성을 제어하는 객체. |
| shape | [IShape](../../com.aspose.slides/ishape) | 원본 모양. |