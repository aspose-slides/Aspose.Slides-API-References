---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: 외부 글꼴에 대한 파일 및 메모리 소스를 제공합니다.
type: docs
url: /ko/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

외부 글꼴에 대한 파일 및 메모리 소스를 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | 글꼴 파일이 포함된 폴더입니다. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | 글꼴 파일이 포함된 폴더입니다. |
| [getMemoryFonts()](#getMemoryFonts--) | 바이트 배열로 표현된 글꼴 컬렉션입니다. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | 바이트 배열로 표현된 글꼴 컬렉션입니다. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

글꼴 파일이 포함된 폴더입니다. 이 폴더에 위치한 모든 글꼴 파일이 컬렉션에 포함됩니다. 재귀적으로 검색되는 폴더입니다.

**반환값:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

글꼴 파일이 포함된 폴더입니다. 이 폴더에 위치한 모든 글꼴 파일이 컬렉션에 포함됩니다. 재귀적으로 검색되는 폴더입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

바이트 배열로 표현된 글꼴 컬렉션입니다.

**반환값:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

바이트 배열로 표현된 글꼴 컬렉션입니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | byte[][] |  |