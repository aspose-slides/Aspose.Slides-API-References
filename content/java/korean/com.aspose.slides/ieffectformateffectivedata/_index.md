---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides for Java API 레퍼런스
description: 유효 효과 서식 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/ieffectformateffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormatEffectiveData extends IEffectParamSource
```

유효 효과 서식 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [IEffectFormat](../../com.aspose.slides/ieffectformat) 인터페이스와 함께 사용되어 상속이 적용된 유효 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | 모든 효과가 비활성화된 경우 (방금 생성된 기본 EffectFormat 객체) true를 반환합니다. |
| [getBlurEffect()](#getBlurEffect--) | 블러 효과. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | 채우기 오버레이 효과. |
| [getGlowEffect()](#getGlowEffect--) | 광택 효과. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | 내부 그림자. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | 외부 그림자. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | 사전 설정 그림자. |
| [getReflectionEffect()](#getReflectionEffect--) | 반사. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | 부드러운 가장자리. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


모든 효과가 비활성화된 경우 (방금 생성된 기본 EffectFormat 객체) true를 반환합니다. 읽기 전용 boolean.

**반환:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlurEffectiveData getBlurEffect()
```


블러 효과. 읽기 전용 [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

**반환:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlayEffectiveData getFillOverlayEffect()
```


채우기 오버레이 효과. 읽기 전용 [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

**반환:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlowEffectiveData getGlowEffect()
```


광택 효과. 읽기 전용 [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).

**반환:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadowEffectiveData getInnerShadowEffect()
```


내부 그림자. 읽기 전용 [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).

**반환:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadowEffectiveData getOuterShadowEffect()
```


외부 그림자. 읽기 전용 [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

**반환:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadowEffectiveData getPresetShadowEffect()
```


사전 설정 그림자. 읽기 전용 [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).

**반환:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflectionEffectiveData getReflectionEffect()
```


반사. 읽기 전용 [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

**반환:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdgeEffectiveData getSoftEdgeEffect()
```


부드러운 가장자리. 읽기 전용 [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).

**반환:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)