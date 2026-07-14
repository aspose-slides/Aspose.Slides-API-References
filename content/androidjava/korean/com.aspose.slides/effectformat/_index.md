---
title: EffectFormat
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 형상의 효과 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/effectformat/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectFormat](../../com.aspose.slides/ieffectformat)
```
public final class EffectFormat extends PVIObject implements IEffectFormat
```

형상의 효과 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNoEffects()](#isNoEffects--) | 모든 효과가 비활성화된 경우 true를 반환합니다(방금 생성된 기본 EffectFormat 객체와 같이). |
| [getBlurEffect()](#getBlurEffect--) | 블러 효과. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | 블러 효과. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | 채우기 오버레이 효과. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | 채우기 오버레이 효과. |
| [getGlowEffect()](#getGlowEffect--) | 글로우 효과. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | 글로우 효과. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | 내부 그림자. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | 내부 그림자. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | 외부 그림자. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | 외부 그림자. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | 프리셋 그림자. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | 프리셋 그림자. |
| [getReflectionEffect()](#getReflectionEffect--) | 반사. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | 반사. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | 소프트 엣지. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | 소프트 엣지. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | 블러 효과를 설정합니다. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | 채우기 오버레이 효과를 활성화합니다. |
| [enableGlowEffect()](#enableGlowEffect--) | 글로우 효과를 활성화합니다. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | 내부 그림자 효과를 활성화합니다. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | 외부 그림자 효과를 활성화합니다. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | 프리셋 그림자 효과를 활성화합니다. |
| [enableReflectionEffect()](#enableReflectionEffect--) | 반사 효과를 활성화합니다. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | 소프트 엣지 효과를 활성화합니다. |
| [disableBlurEffect()](#disableBlurEffect--) | 블러 효과를 비활성화합니다. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | 채우기 오버레이 효과를 비활성화합니다. |
| [disableGlowEffect()](#disableGlowEffect--) | 글로우 효과를 비활성화합니다. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | 내부 그림자 효과를 비활성화합니다. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | 외부 그림자 효과를 비활성화합니다. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | 프리셋 그림자 효과를 비활성화합니다. |
| [disableReflectionEffect()](#disableReflectionEffect--) | 반사 효과를 비활성화합니다. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | 소프트 엣지 효과를 비활성화합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과 포맷 데이터를 가져옵니다. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


버전. 읽기 전용 long.

**반환:**
long
### isNoEffects() {#isNoEffects--}
```
public final boolean isNoEffects()
```


모든 효과가 비활성화된 경우 true를 반환합니다(방금 생성된 기본 EffectFormat 객체와 같이). 읽기 전용 boolean .

**반환:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public final IBlur getBlurEffect()
```


블러 효과. 읽기/쓰기 [IBlur](../../com.aspose.slides/iblur).

**반환:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public final void setBlurEffect(IBlur value)
```


블러 효과. 읽기/쓰기 [IBlur](../../com.aspose.slides/iblur).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public final IFillOverlay getFillOverlayEffect()
```


채우기 오버레이 효과. 읽기/쓰기 [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**반환:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public final void setFillOverlayEffect(IFillOverlay value)
```


채우기 오버레이 효과. 읽기/쓰기 [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |
### getGlowEffect() {#getGlowEffect--}
```
public final IGlow getGlowEffect()
```


글로우 효과. 읽기/쓰기 [IGlow](../../com.aspose.slides/iglow).

**반환:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public final void setGlowEffect(IGlow value)
```


글로우 효과. 읽기/쓰기 [IGlow](../../com.aspose.slides/iglow).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public final IInnerShadow getInnerShadowEffect()
```


내부 그림자. 읽기/쓰기 [IInnerShadow](../../com.aspose.slides/iinnershadow).

**반환:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public final void setInnerShadowEffect(IInnerShadow value)
```


내부 그림자. 읽기/쓰기 [IInnerShadow](../../com.aspose.slides/iinnershadow).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public final IOuterShadow getOuterShadowEffect()
```


외부 그림자. 읽기/쓰기 [IOuterShadow](../../com.aspose.slides/ioutershadow).

**반환:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public final void setOuterShadowEffect(IOuterShadow value)
```


외부 그림자. 읽기/쓰기 [IOuterShadow](../../com.aspose.slides/ioutershadow).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public final IPresetShadow getPresetShadowEffect()
```


프리셋 그림자. 읽기/쓰기 [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**반환:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public final void setPresetShadowEffect(IPresetShadow value)
```


프리셋 그림자. 읽기/쓰기 [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |
### getReflectionEffect() {#getReflectionEffect--}
```
public final IReflection getReflectionEffect()
```


반사. 읽기/쓰기 [IReflection](../../com.aspose.slides/ireflection).

**반환:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public final void setReflectionEffect(IReflection value)
```


반사. 읽기/쓰기 [IReflection](../../com.aspose.slides/ireflection).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public final ISoftEdge getSoftEdgeEffect()
```


소프트 엣지. 읽기/쓰기 [ISoftEdge](../../com.aspose.slides/isoftedge).

**반환:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public final void setSoftEdgeEffect(ISoftEdge value)
```


소프트 엣지. 읽기/쓰기 [ISoftEdge](../../com.aspose.slides/isoftedge).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |
### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public final void setBlurEffect(double radius, boolean grow)
```


블러 효과를 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| radius | double | 반경. |
| grow | boolean | 확장. |
### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public final void enableFillOverlayEffect()
```


채우기 오버레이 효과를 활성화합니다.
### enableGlowEffect() {#enableGlowEffect--}
```
public final void enableGlowEffect()
```


글로우 효과를 활성화합니다.
### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public final void enableInnerShadowEffect()
```


내부 그림자 효과를 활성화합니다.
### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public final void enableOuterShadowEffect()
```


외부 그림자 효과를 활성화합니다.
### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public final void enablePresetShadowEffect()
```


프리셋 그림자 효과를 활성화합니다.
### enableReflectionEffect() {#enableReflectionEffect--}
```
public final void enableReflectionEffect()
```


반사 효과를 활성화합니다.
### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public final void enableSoftEdgeEffect()
```


소프트 엣지 효과를 활성화합니다.
### disableBlurEffect() {#disableBlurEffect--}
```
public final void disableBlurEffect()
```


블러 효과를 비활성화합니다.
### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public final void disableFillOverlayEffect()
```


채우기 오버레이 효과를 비활성화합니다.
### disableGlowEffect() {#disableGlowEffect--}
```
public final void disableGlowEffect()
```


글로우 효과를 비활성화합니다.
### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public final void disableInnerShadowEffect()
```


내부 그림자 효과를 비활성화합니다.
### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public final void disableOuterShadowEffect()
```


외부 그림자 효과를 비활성화합니다.
### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public final void disablePresetShadowEffect()
```


프리셋 그림자 효과를 비활성화합니다.
### disableReflectionEffect() {#disableReflectionEffect--}
```
public final void disableReflectionEffect()
```


반사 효과를 비활성화합니다.
### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public final void disableSoftEdgeEffect()
```


소프트 엣지 효과를 비활성화합니다.
### getEffective() {#getEffective--}
```
public final IEffectFormatEffectiveData getEffective()
```


상속이 적용된 효과 포맷 데이터를 가져옵니다.

--------------------

> ```
> This example demonstrates getting some of shape's effective effect properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IEffectFormatEffectiveData effectiveEffectFormat = pres.getSlides().get_Item(0).Shapes().get_Item(0).getEffectFormat().getEffective();
>  	if (effectiveEffectFormat.isNoEffects())
>  	{
>  		System.out.println("The shape has not effects applied.");
>  	}
>  	else
>  	{
>  		if (effectiveEffectFormat.getBlurEffect() != null)
>  			System.out.println("Blur effect radius: " + effectiveEffectFormat.getBlurEffect().getRadius());
>  		if (effectiveEffectFormat.getFillOverlayEffect() != null)
>  			System.out.println("Fill overlay effect fill type: " + effectiveEffectFormat.getFillOverlayEffect().getFillFormat().getFillType());
>  		if (effectiveEffectFormat.getGlowEffect() != null)
>  			System.out.println("Glow effect color: " + effectiveEffectFormat.getGlowEffect().getColor());
>  		if (effectiveEffectFormat.getInnerShadowEffect() != null)
>  			System.out.println("Inner shadow effect shadow color: " + effectiveEffectFormat.getInnerShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getOuterShadowEffect() != null)
>  			System.out.println("Outer shadow effect shadow color: " + effectiveEffectFormat.getOuterShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getPresetShadowEffect() != null)
>  			System.out.println("Preset shadow effect shadow color: " + effectiveEffectFormat.getPresetShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getReflectionEffect() != null)
>  			System.out.println("Reflection effect distance: " + effectiveEffectFormat.getReflectionEffect().getDistance());
>  		if (effectiveEffectFormat.getSoftEdgeEffect() != null)
>  			System.out.println("Soft edge effect radius: " + effectiveEffectFormat.getSoftEdgeEffect().getRadius());
>  		}
>  	}
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**반환:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - 하나의 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).