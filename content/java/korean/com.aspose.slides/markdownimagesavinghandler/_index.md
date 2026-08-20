---
title: MarkdownSaveOptions.MarkdownImageSavingHandler
second_title: Aspose.Slides for Java API Reference
description: Represents the markdown image saving handler of ImageSavingDelegate.ImageSavingDelegate event.
type: docs
url: /ko/com.aspose.slides/markdownsaveoptions.markdownimagesavinghandler/
---```
public static interface MarkdownSaveOptions.MarkdownImageSavingHandler
```

ImageSavingDelegate.ImageSavingDelegate 이벤트의 markdown 이미지 저장 처리기를 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [invoke(IImage image, int format, String[] link)](#invoke-com.aspose.slides.IImage-int-java.lang.String---) | Markdown 내보내기 중 SVG가 아닌 각 이미지(비트맵 또는 메타파일)에 대해 호출됩니다. |
### invoke(IImage image, int format, String[] link) {#invoke-com.aspose.slides.IImage-int-java.lang.String---}
```
public abstract boolean invoke(IImage image, int format, String[] link)
```

Markdown 내보내기 중 SVG가 아닌 각 이미지(비트맵 또는 메타파일)에 대해 호출됩니다. true를 반환하면 지정된 링크를 사용하고, false를 반환하면 기본 저장 로직을 적용합니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | 내보내는 이미지(비트맵 또는 메타파일)입니다. |
| format | int | 이미지 형식입니다. |
| link | java.lang.String[] | true를 반환할 때 사용할 Markdown 링크입니다. |

**반환값:**
boolean