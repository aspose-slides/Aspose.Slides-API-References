---
title: IPortionFormatEffectiveData
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 효과적인 텍스트 부분 서식 속성을 포함하는 불변 객체.
type: docs
url: /ko/com.aspose.slides/iportionformateffectivedata/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.IBasePortionFormatEffectiveData](../../com.aspose.slides/ibaseportionformateffectivedata)
```
public interface IPortionFormatEffectiveData extends IBasePortionFormatEffectiveData
```

효과적인 텍스트 부분 서식 속성을 포함하는 불변 객체.

--------------------

이 인터페이스는 [IPortionFormat](../../com.aspose.slides/iportionformat) 인터페이스와 함께 사용되어 상속이 적용된 효과적인 서식 값을 반환합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 북마크 식별자를 반환합니다. |
| [getHyperlinkClick()](#getHyperlinkClick--) | 마우스 클릭에 정의된 하이퍼링크를 반환합니다. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | 마우스 오버에 정의된 하이퍼링크를 반환합니다. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

북마크 식별자를 반환합니다. 읽기 전용 String.

**반환:**
java.lang.String
### getHyperlinkClick() {#getHyperlinkClick--}
```
public abstract IHyperlink getHyperlinkClick()
```

마우스 클릭에 정의된 하이퍼링크를 반환합니다. 읽기 전용 [IHyperlink](../../com.aspose.slides/ihyperlink).

**반환:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public abstract IHyperlink getHyperlinkMouseOver()
```

마우스 오버에 정의된 하이퍼링크를 반환합니다. 읽기 전용 [IHyperlink](../../com.aspose.slides/ihyperlink).

**반환:**
[IHyperlink](../../com.aspose.slides/ihyperlink)