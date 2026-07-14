---
title: IBackground
second_title: Java API를 통한 Android용 Aspose.Slides
description: 슬라이드 배경을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibackground/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

슬라이드의 배경을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getType()](#getType--) | 배경 채우기 유형을 반환합니다. |
| [setType(byte value)](#setType-byte-) | 배경 채우기 유형을 반환합니다. |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground 채우기에 대한 FillFormat을 반환합니다. |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground 채우기에 대한 EffectFormat을 반환합니다. |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed 채우기에 대한 ColorFormat을 반환합니다. |
| [getStyleIndex()](#getStyleIndex--) | background theme 컬렉션에서 BackgroundType.Themed 채우기의 인덱스를 반환합니다. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | background theme 컬렉션에서 BackgroundType.Themed 채우기의 인덱스를 반환합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 배경 데이터를 가져옵니다. |
### getType() {#getType--}
```
public abstract byte getType()
```

배경 채우기 유형을 반환합니다. 읽기/쓰기 [BackgroundType](../../com.aspose.slides/backgroundtype).

**반환:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

배경 채우기 유형을 반환합니다. 읽기/쓰기 [BackgroundType](../../com.aspose.slides/backgroundtype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

BackgroundType.OwnBackground 채우기에 대한 FillFormat을 반환합니다. 읽기 전용 [IFillFormat](../../com.aspose.slides/ifillformat).

**반환:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

BackgroundType.OwnBackground 채우기에 대한 EffectFormat을 반환합니다. 읽기 전용 [IEffectFormat](../../com.aspose.slides/ieffectformat).

**반환:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

BackgroundType.Themed 채우기에 대한 ColorFormat을 반환합니다. 읽기 전용 [IColorFormat](../../com.aspose.slides/icolorformat).

**반환:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

background theme 컬렉션에서 BackgroundType.Themed 채우기의 인덱스를 반환합니다. 0은 채우지 않음을 의미합니다. 1..999 - 인덱스. 읽기/쓰기 int.

**반환:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

background theme 컬렉션에서 BackgroundType.Themed 채우기의 인덱스를 반환합니다. 0은 채우지 않음을 의미합니다. 1..999 - 인덱스. 읽기/쓰기 int.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

상속이 적용된 효과적인 배경 데이터를 가져옵니다.

**반환:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).