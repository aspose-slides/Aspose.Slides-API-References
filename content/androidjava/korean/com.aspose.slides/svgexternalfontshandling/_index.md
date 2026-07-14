---
title: SvgExternalFontsHandling
second_title: Java API 레퍼런스를 통해 Android용 Aspose.Slides
description: 텍스트 그리기에 사용되는 외부 폰트를 처리하는 방법을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/svgexternalfontshandling/
---
**상속:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SvgExternalFontsHandling extends System.Enum
```

텍스트 그리기에 사용되는 외부 폰트를 처리하는 방법을 나타냅니다.
## 필드

| 필드 | 설명 |
| --- | --- |
| [AddLinksToFontFiles](#AddLinksToFontFiles) | SVG 파일의 스타일 섹션에 별도의 폰트 파일에 대한 링크를 추가합니다. |
| [Embed](#Embed) | 폰트 데이터를 SVG 파일에 직접 저장합니다. |
| [Vectorize](#Vectorize) | 외부 폰트를 사용하는 모든 텍스트를 그래픽으로 저장합니다. |
### AddLinksToFontFiles {#AddLinksToFontFiles}
```
public static final int AddLinksToFontFiles
```

SVG 파일의 스타일 섹션에 별도의 폰트 파일에 대한 링크를 추가합니다.

### Embed {#Embed}
```
public static final int Embed
```

폰트 데이터를 SVG 파일에 직접 저장합니다. 이 옵션을 사용하기 전에 모든 외부 폰트 라이선스 계약을 확인하십시오.

### Vectorize {#Vectorize}
```
public static final int Vectorize
```

외부 폰트를 사용하는 모든 텍스트를 그래픽으로 저장합니다.