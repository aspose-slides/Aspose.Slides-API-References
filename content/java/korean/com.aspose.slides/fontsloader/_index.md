---
title: FontsLoader
second_title: Aspose.Slides for Java API 레퍼런스
description: 사용자가 정의한 맞춤 글꼴을 로드하기 위한 클래스입니다.
type: docs
url: /ko/com.aspose.slides/fontsloader/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

사용자가 정의한 맞춤 글꼴을 로드하기 위한 클래스입니다. 프레젠테이션 개체를 생성하기 전에 사용해야 합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | 글꼴을 찾기 위해 추가 폴더를 추가합니다. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | 이진 데이터에서 글꼴을 추가합니다. |
| [getFontFolders()](#getFontFolders--) | 글꼴 폴더를 가져옵니다. |
| [clearCache()](#clearCache--) | 사용자가 정의한 모든 맞춤 글꼴을 해제합니다. |

### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

글꼴을 찾기 위해 추가 폴더를 추가합니다.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // 글꼴을 찾을 폴더
>  String[] folders = new String[] { dataDir };
>  // 맞춤 글꼴 디렉터리 폰트를 로드합니다
>  FontsLoader.loadExternalFonts(folders);
>  // 작업을 수행하고 프레젠테이션/슬라이드 렌더링을 실행합니다
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // 글꼴 캐시를 지웁니다
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

매개변수:
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| directories | java.lang.String[] | 추가 글꼴을 읽기 위한 디렉터리입니다. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

이진 데이터에서 글꼴을 추가합니다.

매개변수:
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | byte[] | 글꼴 데이터 |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

글꼴 폴더를 가져옵니다. LoadExternalFonts 메서드로 추가된 폴더와 시스템 글꼴 폴더를 반환합니다.

반환값:
java.lang.String[] - 폴더 이름을 포함하는 배열

### clearCache() {#clearCache--}
```
public static void clearCache()
```

사용자가 정의한 모든 맞춤 글꼴을 해제합니다.

--------------------

이 메서드는 사용자가 정의한 맞춤 글꼴을 사용하여 캐시를 지워야 합니다.