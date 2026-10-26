---
title: SlideShowType
second_title: Aspose.Slides Java API 레퍼런스
description: 기본 슬라이드 쇼 설정.
type: docs
url: /ko/com.aspose.slides/slideshowtype/
---
**상속:**
java.lang.Object
```
public abstract class SlideShowType
```

기본 슬라이드 쇼 설정. 슬라이드 쇼의 유형을 나타내는 조상: [PresentedBySpeaker](../../com.aspose.slides/presentedbyspeaker) 발표자에 의해 표시(전체 화면) [BrowsedByIndividual](../../com.aspose.slides/browsedbyindividual) 개인에 의해 탐색(창) [BrowsedAtKiosk](../../com.aspose.slides/browsedatkiosk) 키오스크에서 탐색(전체 화면)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new PresentedBySpeaker());
>      pres.save("PresentedBySpeaker.pptx", SaveFormat.Pptx);
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("BrowsedByIndividual.pptx", SaveFormat.Pptx);
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("BrowsedAtKiosk.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
