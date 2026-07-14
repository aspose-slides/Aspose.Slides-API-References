---
title: MarkdownSaveOptions.MarkdownSvgImageSavingHandler
second_title: Aspose.Slides for Android용 Java API 참조
description: SvgImageSavingDelegate.SvgImageSavingDelegate 이벤트의 markdown SVG 이미지 저장 핸들러를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/markdownsaveoptions.markdownsvgimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownSvgImageSavingHandler
```

\#SvgImageSavingDelegate.SvgImageSavingDelegate 이벤트의 markdown SVG 이미지 저장 핸들러를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(ISvgImage svgImage, String[] link)](#invoke-com.aspose.slides.ISvgImage-java.lang.String---) | Markdown 내보내기 중 각 SVG 이미지에 대해 호출됩니다. |
### invoke(ISvgImage svgImage, String[] link) {#invoke-com.aspose.slides.ISvgImage-java.lang.String---}
```
public abstract boolean invoke(ISvgImage svgImage, String[] link)
```

Markdown 내보내기 중 각 SVG 이미지에 대해 호출됩니다. 지정된 링크를 사용하려면 true를 반환하고, 기본 저장 로직을 적용하려면 false를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | 내보내는 SVG 이미지. |
| link | java.lang.String[] | true를 반환할 때 사용할 Markdown 링크. |

**반환값:**
boolean