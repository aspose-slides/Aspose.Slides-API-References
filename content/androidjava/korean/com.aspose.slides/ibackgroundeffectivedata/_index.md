---
title: IBackgroundEffectiveData
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 효과적인 배경 속성을 포함하는 불변 객체입니다.
type: docs
url: /ko/com.aspose.slides/ibackgroundeffectivedata/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

효과적인 배경 속성을 포함하는 불변 객체입니다.

--------------------

이 인터페이스는 [IBackground](../../com.aspose.slides/ibackground) 인터페이스와 함께 사용되어 상속이 적용된 효과적인 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 효과적인 채우기 형식을 반환합니다. |
| [getEffectFormat()](#getEffectFormat--) | 효과적인 효과 형식을 반환합니다. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


효과적인 채우기 형식을 반환합니다. 읽기 전용 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**반환:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


효과적인 효과 형식을 반환합니다. 읽기 전용 [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**반환:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)