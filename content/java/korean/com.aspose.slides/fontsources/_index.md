---
title: FontSources
second_title: Aspose.Slides for Java API 참조
description: 외부 글꼴에 대한 파일 및 메모리 소스를 제공합니다.
type: docs
url: /ko/com.aspose.slides/fontsources/
---
**상속:**
java.lang.Object

**모든 구현된 인터페이스:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

외부 글꼴에 대한 파일 및 메모리 소스를 제공합니다.
## 생성자

| Constructor | Description |
| --- | --- |
| [FontSources()](#FontSources--) | 새 기본 글꼴 옵션을 생성합니다. |
## 메서드

| Method | Description |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | 글꼴 파일이 포함된 폴더. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | 글꼴 파일이 포함된 폴더. |
| [getMemoryFonts()](#getMemoryFonts--) | 바이트 배열로 표시된 글꼴 컬렉션. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | 바이트 배열로 표시된 글꼴 컬렉션. |
### FontSources() {#FontSources--}
```
public FontSources()
```

새 기본 글꼴 옵션을 생성합니다.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

글꼴 파일이 포함된 폴더. 이 폴더에 위치한 모든 글꼴 파일이 컬렉션에 포함됩니다. 재귀적으로 검색되는 폴더.

**반환:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

글꼴 파일이 포함된 폴더. 이 폴더에 위치한 모든 글꼴 파일이 컬렉션에 포함됩니다. 재귀적으로 검색되는 폴더.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

바이트 배열로 표시된 글꼴 컬렉션.

**반환:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

바이트 배열로 표시된 글꼴 컬렉션.

**매개변수:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |