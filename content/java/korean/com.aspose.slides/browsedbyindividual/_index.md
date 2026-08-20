---
title: BrowsedByIndividual
second_title: Aspose.Slides for Java API 참조
description: 개별 창으로 탐색
type: docs
url: /ko/com.aspose.slides/browsedbyindividual/
---
**상속:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

개별 브라우징 (창)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | BrowsedByIndividual 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | 창에 스크롤 막대를 표시합니다. |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | 창에 스크롤 막대를 표시합니다. |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

BrowsedByIndividual 클래스의 새 인스턴스를 초기화합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```

창에 스크롤 막대를 표시합니다.

**반환값:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

창에 스크롤 막대를 표시합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | boolean |  |