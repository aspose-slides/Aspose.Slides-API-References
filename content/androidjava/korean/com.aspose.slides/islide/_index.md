---
title: ISlide
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 프레젠테이션의 슬라이드를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/islide/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

프레젠테이션의 슬라이드를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | 슬라이드의 HeaderFooter 관리자를 반환합니다. |
| [getSlideNumber()](#getSlideNumber--) | 슬라이드 번호를 반환합니다. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | 슬라이드 번호를 반환합니다. |
| [getHidden()](#getHidden--) | 지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 확인합니다. |
| [setHidden(boolean value)](#setHidden-boolean-) | 지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 확인합니다. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | 맞춤 스케일링이 적용된 이미지 객체를 반환합니다. |
| [getImage()](#getImage--) | 실제 크기의 20%인 썸네일 이미지 객체를 반환합니다. |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | 지정된 크기의 이미지 객체를 반환합니다. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 지정된 매개변수로 썸네일 TIFF 비트맵 객체를 반환합니다. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | 썸네일 비트맵 객체를 반환합니다. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | 맞춤 스케일링이 적용된 썸네일 비트맵 객체를 반환합니다. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 지정된 크기의 썸네일 비트맵 객체를 반환합니다. |
| [getLayoutSlide()](#getLayoutSlide--) | 현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다. |
| [getNotesSlideManager()](#getNotesSlideManager--) | 노트 슬라이드에 접근하고 추가 및 제거할 수 있게 합니다. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 특정 작성자가 추가한 모든 슬라이드 주석을 반환합니다. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | 슬라이드 내용을 SVG 파일로 저장합니다. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | 슬라이드 내용을 SVG 파일로 저장합니다. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | 슬라이드 내용을 EMF 파일로 저장합니다. |
| [remove()](#remove--) | 프레젠테이션에서 슬라이드를 제거합니다. |
| [reset()](#reset--) | LayoutSlide에 프로토타입이 있는 모든 도형의 위치, 크기 및 서식을 재설정합니다. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

슬라이드의 HeaderFooter 관리자를 반환합니다. 읽기 전용 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**반환:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

슬라이드 번호를 반환합니다. [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) 컬렉션에서 슬라이드의 인덱스는 항상 SlideNumber - 1과 같습니다. 읽기/쓰기 int.

**반환:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

슬라이드 번호를 반환합니다. [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) 컬렉션에서 슬라이드의 인덱스는 항상 SlideNumber - 1과 같습니다. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 확인합니다. 읽기/쓰기 boolean.

**반환:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

지정된 슬라이드가 슬라이드 쇼 중에 숨겨져 있는지 여부를 확인합니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

맞춤 스케일링이 적용된 이미지 객체를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| scaleX | float | x축 방향으로 이 썸네일을 스케일링할 값. |
| scaleY | float | y축 방향으로 이 썸네일을 스케일링할 값. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - 이미지 객체 android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

실제 크기의 20%인 썸네일 이미지 객체를 반환합니다.

**반환:**
[IImage](../../com.aspose.slides/iimage) - 이미지 객체 android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

지정된 크기의 이미지 객체를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | 생성할 이미지의 크기. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - 비트맵 객체.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

지정된 매개변수로 썸네일 TIFF 비트맵 객체를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff 옵션. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - 이미지 객체.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

썸네일 비트맵 객체를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - 비트맵 객체.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

맞춤 스케일링이 적용된 썸네일 비트맵 객체를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |
| scaleX | float | x축 방향으로 이 썸네일을 스케일링할 값. |
| scaleY | float | y축 방향으로 이 썸네일을 스케일링할 값. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - 비트맵 객체.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

지정된 크기의 썸네일 비트맵 객체를 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 렌더링 옵션. |
| imageSize | [Size](../../com.aspose.slides.android/size) | 생성할 이미지의 크기. |

**반환:**
[IImage](../../com.aspose.slides/iimage) - 비트맵 객체.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다. 읽기/쓰기 [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**반환:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

현재 슬라이드의 레이아웃 슬라이드를 반환하거나 설정합니다. 읽기/쓰기 [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

노트 슬라이드에 접근하고 추가 및 제거할 수 있게 합니다. 읽기 전용 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**반환:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

특정 작성자가 추가한 모든 슬라이드 주석을 반환합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 찾을 주석의 작성자 또는 모든 주석을 반환하려면 null. |

**반환:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) 배열.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

슬라이드 내용을 SVG 파일로 저장합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

슬라이드 내용을 SVG 파일로 저장합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 생성 옵션 |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

슬라이드 내용을 EMF 파일로 저장합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 대상 스트림 |

### remove() {#remove--}
```
public abstract void remove()
```

프레젠테이션에서 슬라이드를 제거합니다.

### reset() {#reset--}
```
public abstract void reset()
```

LayoutSlide에 프로토타입이 있는 모든 도형의 위치, 크기 및 서식을 재설정합니다.