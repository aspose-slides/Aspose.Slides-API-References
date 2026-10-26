---
title: IEffectFormat
second_title: Java API를 통한 Android용 Aspose.Slides 참조
description: 모양의 효과 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ieffectformat/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

모양의 효과 속성을 나타냅니다.
## 메서드

| Method | Description |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | 모든 효과가 비활성화된 경우 true를 반환합니다(새로 만든 기본 EffectFormat 개체). |
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
| [getReflectionEffect()](#getReflectionEffect--) | 반사 효과. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | 반사 효과. |
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
| [getEffective()](#getEffective--) | 상속이 적용된 효과 형식 데이터를 가져옵니다. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


모든 효과가 비활성화된 경우 true를 반환합니다(새로 만든 기본 EffectFormat 개체). 읽기 전용 boolean.

**반환값:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```


블러 효과. 읽기/쓰기 [IBlur](../../com.aspose.slides/iblur).

**반환값:**
[IBlur](../../com.aspose.slides/iblur)
### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```


블러 효과. 읽기/쓰기 [IBlur](../../com.aspose.slides/iblur).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```


채우기 오버레이 효과. 읽기/쓰기 [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**반환값:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)
### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```


채우기 오버레이 효과. 읽기/쓰기 [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```


글로우 효과. 읽기/쓰기 [IGlow](../../com.aspose.slides/iglow).

**반환값:**
[IGlow](../../com.aspose.slides/iglow)
### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```


글로우 효과. 읽기/쓰기 [IGlow](../../com.aspose.slides/iglow).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```


내부 그림자. 읽기/쓰기 [IInnerShadow](../../com.aspose.slides/iinnershadow).

**반환값:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)
### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```


내부 그림자. 읽기/쓰기 [IInnerShadow](../../com.aspose.slides/iinnershadow).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```


외부 그림자. 읽기/쓰기 [IOuterShadow](../../com.aspose.slides/ioutershadow).

**반환값:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)
### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```


외부 그림자. 읽기/쓰기 [IOuterShadow](../../com.aspose.slides/ioutershadow).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```


프리셋 그림자. 읽기/쓰기 [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**반환값:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)
### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```


프리셋 그림자. 읽기/쓰기 [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```


반사 효과. 읽기/쓰기 [IReflection](../../com.aspose.slides/ireflection).

**반환값:**
[IReflection](../../com.aspose.slides/ireflection)
### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```


반사 효과. 읽기/쓰기 [IReflection](../../com.aspose.slides/ireflection).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```


소프트 엣지. 읽기/쓰기 [ISoftEdge](../../com.aspose.slides/isoftedge).

**반환값:**
[ISoftEdge](../../com.aspose.slides/isoftedge)
### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```


소프트 엣지. 읽기/쓰기 [ISoftEdge](../../com.aspose.slides/isoftedge).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```


블러 효과를 설정합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| radius | double | 반경. |
| grow | boolean | 증가 여부. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```


채우기 오버레이 효과를 활성화합니다.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```


글로우 효과를 활성화합니다.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```


내부 그림자 효과를 활성화합니다.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```


외부 그림자 효과를 활성화합니다.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```


프리셋 그림자 효과를 활성화합니다.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```


반사 효과를 활성화합니다.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```


소프트 엣지 효과를 활성화합니다.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```


블러 효과를 비활성화합니다.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```


채우기 오버레이 효과를 비활성화합니다.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```


글로우 효과를 비활성화합니다.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```


내부 그림자 효과를 비활성화합니다.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```


외부 그림자 효과를 비활성화합니다.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```


프리셋 그림자 효과를 비활성화합니다.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```


반사 효과를 비활성화합니다.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```


소프트 엣지 효과를 비활성화합니다.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```


상속이 적용된 효과 형식 데이터를 가져옵니다.

**반환값:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - A [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).