---
title: IPortionFormat
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 이 클래스는 텍스트 부분 서식 속성을 포함합니다.
type: docs
url: /ko/com.aspose.slides/iportionformat/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

이 클래스는 텍스트 부분 서식 속성을 포함합니다. [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)와 달리 이 클래스의 모든 속성은 쓰기 가능합니다.

--------------------

이 클래스는 특정 부분에 정의된 텍스트 부분 서식 속성을 반환하고 조작하는 데 사용됩니다. 이는 값을 가져올 때 상속이 적용되지 않으므로 대부분의 경우 \"정의되지 않음\"을 의미하는 값을 얻게 됩니다.

상속을 포함한 효과적인 서식 매개변수 값을 얻으려면 [getEffective](../../com.aspose.slides/iportionformat\#getEffective) 메서드를 사용해야 하며, 이 메서드는 [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) 인스턴스를 반환합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | 북마크 식별자를 반환하거나 설정합니다. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | 북마크 식별자를 반환하거나 설정합니다. |
| [getSmartTagClean()](#getSmartTagClean--) | 스마트 태그를 정리해야 하는지 여부를 결정합니다. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | 스마트 태그를 정리해야 하는지 여부를 결정합니다. |
| [getEffective()](#getEffective--) | 상속이 적용된 효과적인 부분 서식 데이터를 가져옵니다. |

### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

북마크 식별자를 반환하거나 설정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

북마크 식별자를 반환하거나 설정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

스마트 태그를 정리해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 boolean.

**반환값:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

스마트 태그를 정리해야 하는지 여부를 결정합니다. 상속이 적용되지 않습니다. 읽기/쓰기 boolean.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

상속이 적용된 효과적인 부분 서식 데이터를 가져옵니다.

**반환값:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).