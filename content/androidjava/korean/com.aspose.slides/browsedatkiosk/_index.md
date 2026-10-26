---
title: BrowsedAtKiosk
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 키오스크에서 전체 화면으로 보기
type: docs
url: /ko/com.aspose.slides/browsedatkiosk/
---
**상속:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedAtKiosk extends SlideShowType
```

키오스크에서 보기 (전체 화면)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BrowsedAtKiosk()](#BrowsedAtKiosk--) | BrowsedAtKiosk 클래스의 새 인스턴스를 초기화합니다. |
### BrowsedAtKiosk() {#BrowsedAtKiosk--}
```
public BrowsedAtKiosk()
```


BrowsedAtKiosk 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedAtKiosk());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```