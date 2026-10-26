---
title: Background
second_title: Aspose.Slides Java API 레퍼런스
description: 슬라이드의 배경을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/background/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

슬라이드의 배경을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 배경 채우기의 유형을 반환합니다. |
| [setType(byte value)](#setType-byte-) | 배경 채우기의 유형을 반환합니다. |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground 채우기에 대한 FillFormat을 반환합니다. |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground 채우기에 대한 EffectFormat을 반환합니다. |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed 채우기에 대한 ColorFormat을 반환합니다. |
| [getStyleIndex()](#getStyleIndex--) | 배경 테마 컬렉션에서 BackgroundType.Themed 채우기의 인덱스를 반환합니다. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | 배경 테마 컬렉션에서 BackgroundType.Themed 채우기의 인덱스를 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 배경 데이터를 가져옵니다. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | 도형의 부모 슬라이드를 반환합니다. |
| [getPresentation()](#getPresentation--) | 슬라이드의 부모 프레젠테이션을 반환합니다. |
### getType() {#getType--}
```
public final byte getType()
```

배경 채우기의 유형을 반환합니다. 읽기/쓰기 [BackgroundType](../../com.aspose.slides/backgroundtype).

**반환값:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

배경 채우기의 유형을 반환합니다. 읽기/쓰기 [BackgroundType](../../com.aspose.slides/backgroundtype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

BackgroundType.OwnBackground 채우기에 대한 FillFormat을 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환값:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

BackgroundType.OwnBackground 채우기에 대한 EffectFormat을 반환합니다. 읽기 전용 [IEffectFormat](../../com.aspose.slides/ieffectformat).

**반환값:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

BackgroundType.Themed 채우기에 대한 ColorFormat을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환값:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

배경 테마 컬렉션에서 BackgroundType.Themed 채우기의 인덱스를 반환합니다. 0은 채우기가 없음을 의미합니다. 1..999 - 인덱스. 읽기/쓰기 int.

**반환값:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

배경 테마 컬렉션에서 BackgroundType.Themed 채우기의 인덱스를 반환합니다. 0은 채우기가 없음을 의미합니다. 1..999 - 인덱스. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

상속이 적용된 효과적인 배경 데이터를 가져옵니다.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**반환값:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

도형의 부모 슬라이드를 반환합니다. 읽기 전용 [IBaseSlide](../../com.aspose.slides/ibaseslide).

**반환값:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

슬라이드의 부모 프레젠테이션을 반환합니다. 읽기 전용 [IPresentation](../../com.aspose.slides/ipresentation).

**반환값:**
[Presentation](../../com.aspose.slides/presentation)