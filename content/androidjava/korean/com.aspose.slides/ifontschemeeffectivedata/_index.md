---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 효과적인 폰트 스킴 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

효과적인 폰트 스킴 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMinor()](#getMinor--) | 슬라이드의 "body" 부분에 대한 폰트 컬렉션을 반환합니다. |
| [getMajor()](#getMajor--) | 슬라이드의 "heading" 부분에 대한 폰트 컬렉션을 반환합니다. |
| [getName()](#getName--) | 폰트 스킴 이름을 반환합니다. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```


슬라이드의 "body" 부분에 대한 폰트 컬렉션을 반환합니다. 읽기 전용 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**반환:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```


슬라이드의 "heading" 부분에 대한 폰트 컬렉션을 반환합니다. 읽기 전용 [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**반환:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```


폰트 스킴 이름을 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String