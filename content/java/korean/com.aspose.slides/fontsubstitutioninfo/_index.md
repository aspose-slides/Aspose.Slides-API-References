---
title: FontSubstitutionInfo
second_title: Aspose.Slides for Java API 레퍼런스
description: 이 구조는 렌더링될 때 폰트 교체에 대한 정보를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/fontsubstitutioninfo/
---
**상속:**
java.lang.Object
```
public class FontSubstitutionInfo
```

이 구조는 렌더링될 때 폰트 교체에 대한 정보를 나타냅니다.

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

| Constructor | Description |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 클래스의 인스턴스를 생성합니다. |
## 메서드

| Method | Description |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | 프레젠테이션에서 원본 폰트 이름을 표시합니다. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | 원본 폰트에 대한 교체 폰트 이름을 표시합니다. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

[FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) 클래스의 인스턴스를 생성합니다.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| originFontName | java.lang.String | 프레젠테이션 문자열의 원본 폰트 이름 String |
| substFontName | java.lang.String | 원본 폰트에 대한 교체 폰트 이름 String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

프레젠테이션에서 원본 폰트 이름을 표시합니다. 읽기 전용 String

**반환값:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

원본 폰트에 대한 교체 폰트 이름을 표시합니다. 읽기 전용 String

**반환값:**
java.lang.String