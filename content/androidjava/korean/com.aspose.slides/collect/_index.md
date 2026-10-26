---
title: Collect
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 다양한 유형의 모델 객체를 수집하기 위한 메서드 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/collect/
---
**상속:**
java.lang.Object
```
public class Collect
```

[Presentation](../../com.aspose.slides/presentation)에서 다양한 유형의 모델 객체를 수집하기 위한 메서드 그룹을 나타냅니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... 모양 서식이나 기타 속성을 변경합니다
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Collect()](#Collect--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | [Shape](../../com.aspose.slides/shape)의 모든 인스턴스를 [Presentation](../../com.aspose.slides/presentation)에서 수집합니다. |
### Collect() {#Collect--}
```
public Collect()
```

### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```

[Shape](../../com.aspose.slides/shape)의 모든 인스턴스를 [Presentation](../../com.aspose.slides/presentation)에서 수집합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // shape가 AutoShape인 경우, 검은색 실선 테두리를 추가합니다
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 쉐이프를 수집할 프레젠테이션 |

**반환값:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - 프레젠테이션에 포함된 모든 쉐이프의 컬렉션