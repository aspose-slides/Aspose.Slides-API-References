---
title: IMasterTheme
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 마스터 테마를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/imastertheme/
---
**모든 구현된 인터페이스:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

마스터 테마를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 추가 색 구성표 컬렉션을 반환합니다. |
| [getName()](#getName--) | 테마의 이름을 반환합니다. |
| [setName(String value)](#setName-java.lang.String-) | 테마의 이름을 반환합니다. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

추가 색 구성표 컬렉션을 반환합니다. 이 스키마는 프레젠테이션의 모양에 영향을 주지 않으며, 슬라이드의 기본 색 구성표로 선택할 수 있습니다. 읽기 전용 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**반환:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

테마의 이름을 반환합니다. 읽기/쓰기 String.

**반환:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

테마의 이름을 반환합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |