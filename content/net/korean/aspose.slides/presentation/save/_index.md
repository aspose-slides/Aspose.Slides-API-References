---
title: Save
second_title: Aspose.Sildes .NET API 레퍼런스
description: 프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장합니다.
type: docs
weight: 390
url: /ko/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장합니다.

```csharp
public void Save(string fname, SaveFormat format)
```

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | 생성된 파일의 경로. |
| format | SaveFormat | 내보낸 데이터의 형식. |

### 관련 항목

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장합니다.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | 출력 스트림. |
| format | SaveFormat | 내보낸 데이터의 형식. |

### 관련 항목

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### 관련 항목

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장하고 추가 옵션을 적용합니다.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | 출력 스트림. |
| format | SaveFormat | 내보낸 데이터의 형식. |
| options | ISaveOptions | 추가 형식 옵션. |

### 예외

| 예외 | 조건 |
| --- | --- |
| NotSupportedException | 암호화된 파일을 Office 2007-2010 형식이 아닌 형식으로 저장하려고 하면 |
 
### 관련 항목

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합에 저장합니다.

```csharp
public void Save(IXamlOptions options)
```

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| options | IXamlOptions | XAML 형식 옵션. |

### 예제

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### 관련 항목

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

프레젠테이션의 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 파일에 저장합니다.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | 생성된 파일의 경로. |
| slides | Int32[] | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | SaveFormat | 내보낸 데이터의 형식. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | 스트림 또는 슬라이드 매개 변수가 null인 경우. |
| ArgumentOutOfRangeException | 슬라이드 매개 변수가 잘못된 페이지 번호를 포함하는 경우. |
| InvalidOperationException | 지원되지 않는 SaveFormat을 사용할 때, 예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 관련 항목

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

프레젠테이션의 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 파일에 저장하고 추가 옵션을 적용합니다.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | 생성된 파일의 경로. |
| slides | Int32[] | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | SaveFormat | 내보낸 데이터의 형식. |
| options | ISaveOptions | 추가 형식 옵션. |

### 관련 항목

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

프레젠테이션의 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 스트림에 저장합니다.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | 출력 스트림. |
| slides | Int32[] | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | SaveFormat | 내보낸 데이터의 형식. |

### 관련 항목

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

프레젠테이션의 지정된 슬라이드를 페이지 번호를 유지하면서 지정된 형식의 스트림에 저장하고 추가 옵션을 적용합니다.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | 출력 스트림. |
| slides | Int32[] | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | SaveFormat | 내보낸 데이터의 형식. |
| options | ISaveOptions | 추가 형식 옵션. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | 스트림 또는 슬라이드 매개 변수가 null인 경우. |
| ArgumentOutOfRangeException | 슬라이드 매개 변수가 잘못된 페이지 번호를 포함하는 경우. |
| InvalidOperationException | 지원되지 않는 SaveFormat을 사용할 때, 예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 예제

다음 예제는 PowerPoint를 PNG로 변환하는 방법을 보여줍니다.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail().Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

다음 예제는 맞춤 치수로 PowerPoint를 PNG로 변환하는 방법을 보여줍니다.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    float scaleX = 2f;
    float scaleY = 2f;
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(scaleX, scaleY).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

다음 예제는 맞춤 크기로 PowerPoint를 PNG로 변환하는 방법을 보여줍니다.

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    Size size = new Size(960, 720);
    for (var index = 0; index < pres.Slides.Count; index++)
    {
        ISlide slide = pres.Slides[index];
        slide.GetThumbnail(size).Save($"slide_{index}.png", ImageFormat.Png);
    }
}
```

### 관련 항목

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* class [Presentation](../../presentation)
* namespace [Aspose.Slides](../../presentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->