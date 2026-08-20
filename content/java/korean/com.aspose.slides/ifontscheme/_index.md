---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
description: Stores theme-defined fonts.
type: docs
url: /ko/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

Stores theme-defined fonts.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getMinor()](#getMinor--) | 슬라이드의 "body" 부분에 대한 글꼴 컬렉션을 반환합니다. |
| [getMajor()](#getMajor--) | 슬라이드의 "heading" 부분에 대한 글꼴 컬렉션을 반환합니다. |
| [getName()](#getName--) | 폰트 스키마 이름을 반환합니다. |
| [setName(String value)](#setName-java.lang.String-) | 폰트 스키마 이름을 반환합니다. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


슬라이드의 "body" 부분에 대한 글꼴 컬렉션을 반환합니다. 읽기 전용 [IFonts](../../com.aspose.slides/ifonts).

**반환:**  
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


슬라이드의 "heading" 부분에 대한 글꼴 컬렉션을 반환합니다. 읽기 전용 [IFonts](../../com.aspose.slides/ifonts).

**반환:**  
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


폰트 스키마 이름을 반환합니다. 읽기/쓰기 String.

**반환:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


폰트 스키마 이름을 반환합니다. 읽기/쓰기 String.

**매개변수:**  
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |