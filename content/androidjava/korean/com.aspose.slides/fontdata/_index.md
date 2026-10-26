---
title: FontData
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 폰트 정의를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/fontdata/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

폰트 정의를 나타냅니다. 불변.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | 지정된 글꼴 이름으로 새 FontData 객체를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFontName()](#getFontName--) | 글꼴 이름을 반환합니다. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | 테마 참조를 실제 사용된 글꼴로 교체하여 글꼴 이름을 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 FontData 인스턴스가 같은지 여부를 판단합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수로 작동하며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용할 수 있습니다. |
| [toString()](#toString--) | 문자열 표현을 반환합니다. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

지정된 글꼴 이름으로 새 FontData 객체를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | java.lang.String | 글꼴 이름. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

글꼴 이름을 반환합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

테마 참조를 실제 사용된 글꼴로 교체하여 글꼴 이름을 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | 테마가 테마 글꼴 이름을 가져와야 하는 테마입니다. 호출자가 올바른 값을 제공해야 합니다. [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective)를 참조하십시오. |

**반환값:**
java.lang.String - 글꼴 이름.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

두 FontData 인스턴스가 같은지 여부를 판단합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 FontData와 비교할 FontData. |

**반환값:**
boolean - **true** if the specified FontData is equal to the current FontData; otherwise, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수로 작동하며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에 사용할 수 있습니다.

**반환값:**
int - FontData의 해시 코드.
### toString() {#toString--}
```
public String toString()
```

문자열 표현을 반환합니다.

**반환값:**
java.lang.String - 문자열 표현.