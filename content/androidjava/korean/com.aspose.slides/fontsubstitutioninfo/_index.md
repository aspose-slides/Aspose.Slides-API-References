---
title: FontSubstitutionInfo
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: 이 구조체는 렌더링 시 폰트 교체에 대한 정보를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/fontsubstitutioninfo/
---
**상속:**
java.lang.Object
```
public class FontSubstitutionInfo
```

This structure represents the information about the font replacement when it will be rendered.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 클래스의 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | 프레젠테이션에서 소스 글꼴 이름을 나타냅니다. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | 원본 글꼴에 대한 대체 글꼴 이름을 나타냅니다. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

[FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 클래스의 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| originFontName | java.lang.String | 프레젠테이션의 소스 글꼴 이름 String |
| substFontName | java.lang.String | 원본 글꼴에 대한 대체 글꼴 이름 String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

프레젠테이션에서 소스 글꼴 이름을 나타냅니다. 읽기 전용 String

**반환값:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

원본 글꼴에 대한 대체 글꼴 이름을 나타냅니다. 읽기 전용 String

**반환값:**
java.lang.String