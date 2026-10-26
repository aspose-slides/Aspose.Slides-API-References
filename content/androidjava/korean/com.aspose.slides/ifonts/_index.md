---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: 폰트 컬렉션을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ifonts/
---```
public interface IFonts
```

폰트 컬렉션을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | 라틴 글꼴을 반환하거나 설정합니다. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | 라틴 글꼴을 반환하거나 설정합니다. |
| [getEastAsianFont()](#getEastAsianFont--) | 동아시아 글꼴을 반환하거나 설정합니다. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | 동아시아 글꼴을 반환하거나 설정합니다. |
| [getComplexScriptFont()](#getComplexScriptFont--) | 복합 스크립트 글꼴을 반환하거나 설정합니다. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | 복합 스크립트 글꼴을 반환하거나 설정합니다. |
| [getScriptFontMap()](#getScriptFontMap--) | 프레젠테이션에 있는 모든 스크립트 글꼴 정의의 사전을 반환합니다. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | 프레젠테이션 테마에서 특정 스크립트 태그와 연결된 글꼴 이름을 가져옵니다. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 특정 스크립트 태그에 글꼴 이름을 할당하여 해당 스크립트 텍스트가 프레젠테이션에서 어떻게 렌더링될지 정의합니다. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | 테마의 글꼴 컬렉션에서 특정 스크립트 태그와 연결된 글꼴 설정을 제거합니다. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```


라틴 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```


라틴 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```


동아시아 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


동아시아 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


복합 스크립트 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


복합 스크립트 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


프레젠테이션에 있는 모든 스크립트 글꼴 정의의 사전을 반환합니다.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**반환:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - 스크립트 코드를 글꼴 이름에 매핑하는 사전.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```


프레젠테이션 테마에서 특정 스크립트 태그와 연결된 글꼴 이름을 가져옵니다.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| script | java.lang.String | BCP-47 스크립트 코드(예: "Latn", "Cyrl", "Jpan")로 식별되는 문자 체계입니다. |

**반환:**
java.lang.String - 지정된 스크립트에 사용되는 글꼴 이름이며, 스크립트가 정의되지 않은 경우  null  입니다.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


특정 스크립트 태그에 글꼴 이름을 할당하여 해당 스크립트 텍스트가 프레젠테이션에서 어떻게 렌더링될지 정의합니다.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| script | java.lang.String | BCP-47 스크립트 코드(예: "Arab", "Hebr", "Hans")로 식별되는 문자 체계입니다. |
| fontName | java.lang.String | 지정된 스크립트에 할당할 글꼴 이름입니다. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


테마의 글꼴 컬렉션에서 특정 스크립트 태그와 연결된 글꼴 설정을 제거합니다.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| script | java.lang.String | 글꼴 설정을 제거해야 하는 BCP-47 스크립트 코드입니다. |