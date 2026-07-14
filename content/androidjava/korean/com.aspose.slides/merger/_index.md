---
title: Merger
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 동일한 형식의 PowerPoint 프레젠테이션을 하나의 파일로 병합하기 위한 메서드 그룹을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/merger/
---
**상속:**
java.lang.Object
```
public class Merger
```

동일한 형식의 PowerPoint 프레젠테이션을 하나의 파일로 병합하기 위한 메서드 그룹을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [process(String[] inputFileNames, String outputFileName)](#process-java.lang.String---java.lang.String-) | 동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다. |
| [process(String[] inputFileNames, String outputFileName, ISaveOptions options)](#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-) | 동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다. |
| [process(String[] inputFileNames, OutputStream outputStream)](#process-java.lang.String---java.io.OutputStream-) | 동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다. |
| [process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)](#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-) | 동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다. |
### process(String[] inputFileNames, String outputFileName) {#process-java.lang.String---java.lang.String-}
```
public static void process(String[] inputFileNames, String outputFileName)
```


동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다.

--------------------

> ```
> Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, "merged.ppt");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| outputFileName | java.lang.String | 병합된 프레젠테이션 파일의 결과 출력 파일 이름입니다. |

### process(String[] inputFileNames, String outputFileName, ISaveOptions options) {#process-java.lang.String---java.lang.String-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, String outputFileName, ISaveOptions options)
```


동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, "merged.pptx", options);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| outputFileName | java.lang.String | 병합된 프레젠테이션 파일의 결과 출력 파일 이름입니다. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 병합된 프레젠테이션이 저장되는 방식을 정의하는 추가 옵션입니다. |

### process(String[] inputFileNames, OutputStream outputStream) {#process-java.lang.String---java.io.OutputStream-}
```
public static void process(String[] inputFileNames, OutputStream outputStream)
```


동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다.

--------------------

> ```
> ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.ppt", "pres2.ppt" }, stream);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| outputStream | java.io.OutputStream | 출력 스트림입니다. |

### process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options) {#process-java.lang.String---java.io.OutputStream-com.aspose.slides.ISaveOptions-}
```
public static void process(String[] inputFileNames, OutputStream outputStream, ISaveOptions options)
```


동일한 형식의 여러 PowerPoint 프레젠테이션을 하나의 프레젠테이션 파일로 병합합니다.

--------------------

> ```
> PptxOptions options = new PptxOptions();
>  options.setRefreshThumbnail(false);
>  ByteArrayOutputStream stream = new ByteArrayOutputStream();
>  Merger.process(new String[] { "pres1.pptx", "pres2.pptx" }, stream, options);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputFileNames | java.lang.String[] | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| outputStream | java.io.OutputStream | 출력 스트림입니다. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | 병합된 프레젠테이션이 저장되는 방식을 정의하는 추가 옵션입니다. |