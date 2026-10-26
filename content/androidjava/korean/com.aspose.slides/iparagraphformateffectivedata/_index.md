---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 효과적인 단락 서식 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

효과적인 단락 서식 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 인터페이스와 함께 사용되어 상속이 적용된 효과적인 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBullet()](#getBullet--) | 단락의 글머리표 형식을 반환합니다. |
| [getDepth()](#getDepth--) | 단락의 깊이를 반환합니다. |
| [getAlignment()](#getAlignment--) | 단락의 텍스트 정렬을 반환합니다. |
| [getSpaceWithin()](#getSpaceWithin--) | 단락의 기준선 사이의 간격을 반환합니다. |
| [getSpaceBefore()](#getSpaceBefore--) | 단락의 첫 번째 줄 앞의 간격을 반환합니다. |
| [getSpaceAfter()](#getSpaceAfter--) | 단락의 마지막 줄 뒤의 간격을 반환합니다. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | 단락에서 동아시아 줄 바꿈이 사용되는지 여부를 결정합니다. |
| [getRightToLeft()](#getRightToLeft--) | 단락에서 오른쪽에서 왼쪽 쓰기가 사용되는지 여부를 결정합니다. |
| [getLatinLineBreak()](#getLatinLineBreak--) | 단락에서 라틴 줄 바꿈이 사용되는지 여부를 결정합니다. |
| [getHangingPunctuation()](#getHangingPunctuation--) | 단락에서 걸려 있는 구두점이 사용되는지 여부를 결정합니다. |
| [getMarginLeft()](#getMarginLeft--) | 단락의 왼쪽 여백을 반환합니다. |
| [getMarginRight()](#getMarginRight--) | 단락의 오른쪽 여백을 반환합니다. |
| [getIndent()](#getIndent--) | 단락 첫 줄 들여쓰기/걸려 있는 들여쓰기를 반환합니다. |
| [getDefaultTabSize()](#getDefaultTabSize--) | 기본 탭 크기를 반환합니다. |
| [getTabs()](#getTabs--) | 단락의 탭을 반환합니다. |
| [getFontAlignment()](#getFontAlignment--) | 단락의 글꼴 정렬을 반환합니다. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | 단락의 기본 부분 형식을 반환합니다. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


단락의 글머리표 형식을 반환합니다. 읽기 전용 [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**반환:**  
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


단락의 깊이를 반환합니다. 읽기 전용 short.

**반환:**  
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


단락의 텍스트 정렬을 반환합니다. 읽기 전용 [TextAlignment](../../com.aspose.slides/textalignment).

**반환:**  
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


단락의 기준선 사이의 간격을 반환합니다. 읽기 전용 float.

**반환:**  
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


단락의 첫 번째 줄 앞의 간격을 반환합니다. 읽기 전용 float.

**반환:**  
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


단락의 마지막 줄 뒤의 간격을 반환합니다. 읽기 전용 float.

**반환:**  
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


단락에서 동아시아 줄 바꿈이 사용되는지 여부를 결정합니다. 읽기 전용 boolean.

**반환:**  
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


단락에서 오른쪽에서 왼쪽 쓰기가 사용되는지 여부를 결정합니다. 읽기 전용 boolean.

**반환:**  
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


단락에서 라틴 줄 바꿈이 사용되는지 여부를 결정합니다. 읽기 전용 boolean.

**반환:**  
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


단락에서 걸려 있는 구두점이 사용되는지 여부를 결정합니다. 읽기 전용 boolean.

**반환:**  
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


단락의 왼쪽 여백을 반환합니다. 읽기 전용 float.

**반환:**  
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


단락의 오른쪽 여백을 반환합니다. 읽기 전용 float.

**반환:**  
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


단락 첫 줄 들여쓰기/걸려 있는 들여쓰기를 반환합니다. 걸려 있는 들여쓰기는 음수 값으로 정의될 수 있습니다. 읽기 전용 float.

**반환:**  
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


기본 탭 크기를 반환합니다. 읽기 전용 float.

**반환:**  
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


단락의 탭을 반환합니다. 읽기 전용 ITabEffectiveData[].

**반환:**  
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


단락의 글꼴 정렬을 반환합니다. 읽기 전용 [FontAlignment](../../com.aspose.slides/fontalignment).

**반환:**  
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


단락의 기본 부분 형식을 반환합니다. 읽기 전용 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**반환:**  
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)