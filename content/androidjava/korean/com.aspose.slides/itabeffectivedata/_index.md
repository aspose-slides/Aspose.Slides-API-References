---
title: ITabEffectiveData
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 효과적인 텍스트 탭 정지 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/itabeffectivedata/
---
**모든 구현된 인터페이스:**
java.lang.Comparable
```
public interface ITabEffectiveData extends Comparable
```

텍스트의 실제 탭 정지 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)의 일부로 사용됩니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPosition()](#getPosition--) | 탭의 위치를 반환합니다. |
| [getAlignment()](#getAlignment--) | 탭의 정렬 스타일을 반환합니다. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

탭의 위치를 반환합니다. 이 속성을 할당하면 컬렉션에서 탭의 인덱스가 변경되고 Enumerator가 무효화될 수 있습니다. 읽기 전용 double.

**반환값:**
double
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

탭의 정렬 스타일을 반환합니다. 읽기 전용 [TabAlignment](../../com.aspose.slides/tabalignment).

**반환값:**
int