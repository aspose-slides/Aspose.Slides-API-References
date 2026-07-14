---
title: IFormat
second_title: Aspose.Slides for Android via Java API Reference
description: 차트 형식 속성을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iformat/
---```
public interface IFormat
```

차트 형식 속성을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFill()](#getFill--) | 차트의 채우기 스타일 속성을 반환합니다. |
| [getLine()](#getLine--) | 차트의 선 스타일 속성을 반환합니다. |
| [getEffect()](#getEffect--) | 차트에 사용되는 효과를 반환합니다. |
| [getEffect3D()](#getEffect3D--) | 차트의 3D 형식을 반환합니다. |
### getFill() {#getFill--}
```
public abstract IFillFormat getFill()
```


차트의 채우기 스타일 속성을 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getLine() {#getLine--}
```
public abstract ILineFormat getLine()
```


차트의 선 스타일 속성을 반환합니다. 읽기 전용 [ILineFormat](../../com.aspose.slides/ilineformat).

**반환:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffect() {#getEffect--}
```
public abstract IEffectFormat getEffect()
```


차트에 사용되는 효과를 반환합니다. 읽기 전용 [IEffectFormat](../../com.aspose.slides/ieffectformat).

**반환:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getEffect3D() {#getEffect3D--}
```
public abstract IThreeDFormat getEffect3D()
```


차트의 3D 형식을 반환합니다. 읽기 전용 [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**반환:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)