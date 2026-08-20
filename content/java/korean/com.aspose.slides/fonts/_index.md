---
title: Fonts
second_title: Aspose.Slides for Java API 레퍼런스
description: 글꼴 컬렉션.
type: docs
url: /ko/com.aspose.slides/fonts/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

글꼴 컬렉션.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | 프레젠테이션의 모든 스크립트 글꼴 정의를 포함하는 사전을 반환합니다. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | 프레젠테이션 테마에서 특정 스크립트 태그와 연결된 글꼴 이름을 가져옵니다. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | 특정 스크립트 태그에 글꼴 이름을 할당하여 해당 스크립트 텍스트가 프레젠테이션에서 어떻게 렌더링되는지 정의합니다. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | 테마의 글꼴 컬렉션에서 특정 스크립트 태그와 연결된 글꼴 설정을 제거합니다. |
| [getLatinFont()](#getLatinFont--) | Latin 글꼴을 반환하거나 설정합니다. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Latin 글꼴을 반환하거나 설정합니다. |
| [getEastAsianFont()](#getEastAsianFont--) | East Asian 글꼴을 반환하거나 설정합니다. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | East Asian 글꼴을 반환하거나 설정합니다. |
| [getComplexScriptFont()](#getComplexScriptFont--) | complex script 글꼴을 반환하거나 설정합니다. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | complex script 글꼴을 반환하거나 설정합니다. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


프레젠테이션의 모든 스크립트 글꼴 정의를 포함하는 사전을 반환합니다.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**반환값:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - 스크립트 코드를 글꼴 이름에 매핑하는 사전.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
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
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | 쓰기 시스템을 식별하는 BCP-47 스크립트 코드(예: "Latn", "Cyrl", "Jpan")입니다. |

**반환값:**
java.lang.String - 지정된 스크립트에 사용되는 글꼴 이름이며, 스크립트가 정의되지 않은 경우  null  입니다.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


특정 스크립트 태그에 글꼴 이름을 할당하여 해당 스크립트 텍스트가 프레젠테이션에서 어떻게 렌더링되는지 정의합니다.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | 쓰기 시스템을 식별하는 BCP-47 스크립트 코드(예: "Arab", "Hebr", "Hans")입니다. |
| fontName | java.lang.String | 지정된 스크립트에 할당할 글꼴 이름입니다. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


테마의 글꼴 컬렉션에서 특정 스크립트 태그와 연결된 글꼴 설정을 제거합니다.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**매개변수:**
| Parameter | Type | Description |
| --- | --- | |
| script | java.lang.String | 제거해야 하는 글꼴 설정이 있는 BCP-47 스크립트 코드입니다. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```


Latin 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환값:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


Latin 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


East Asian 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환값:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


East Asian 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


complex script 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**반환값:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


complex script 글꼴을 반환하거나 설정합니다. 읽기/쓰기 [IFontData](../../com.aspose.slides/ifontdata).

**매개변수:**
| Parameter | Type | Description |
| --- | --- | |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |