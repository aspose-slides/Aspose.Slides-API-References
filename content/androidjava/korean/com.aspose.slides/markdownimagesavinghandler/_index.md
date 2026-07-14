---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: ImageSavingDelegate.ImageSavingDelegate 이벤트의 markdown 이미지 저장 핸들러를 나타냅니다.
type: docs
url: /ko/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

ImageSavingDelegate.ImageSavingDelegate 이벤트의 markdown 이미지 저장 핸들러를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Markdown 내보내기 중 SVG가 아닌 각 이미지(비트맵 또는 메타파일)에 대해 호출됩니다. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Markdown 내보내기 중 SVG가 아닌 각 이미지(비트맵 또는 메타파일)에 대해 호출됩니다. 지정된 링크를 사용하려면 true를 반환하고, 기본 저장 로직을 적용하려면 false를 반환합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 내보내는 이미지(비트맵 또는 메타파일)입니다. |
| format | int | 이미지 형식입니다. |
| link | java.lang.String[] | true를 반환할 때 사용할 Markdown 링크입니다. |

**반환값:**
boolean