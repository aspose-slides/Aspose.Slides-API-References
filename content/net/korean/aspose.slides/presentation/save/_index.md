---
title: Save
second_title: Aspose.Sildes for .NET API 참조
description: 프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장합니다.
type: docs
weight: 400
url: /ko/aspose.slides/presentation/save/
---
## Save(string, SaveFormat) {#save_5}

프레젠테이션의 모든 슬라이드를 지정된 형식으로 파일에 저장합니다.

```csharp
public void Save(string fname, SaveFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| format | SaveFormat | Format of the exported data. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장합니다.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 인터페이스 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

프레젠테이션의 모든 슬라이드를 지정된 형식으로 스트림에 저장하고 추가 옵션을 적용합니다.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 예외

| 예외 | 조건 |
| --- | --- |
| NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 인터페이스 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

---

## Save(IXamlOptions) {#save}

프레젠테이션의 모든 슬라이드를 XAML 마크업을 나타내는 파일 집합에 저장합니다.

```csharp
public void Save(IXamlOptions options)
```

| 매개변수 | 형식 | 설명 |
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

### 참조

* 인터페이스 [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

프레젠테이션에서 지정된 슬라이드를 페이지 번호를 유지한 상태로 지정된 형식의 파일에 저장합니다.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | stream 또는 slides 매개변수가 null인 경우. |
| ArgumentOutOfRangeException | slides 매개변수에 잘못된 페이지 번호가 포함된 경우. |
| InvalidOperationException | 지원되지 않는 SaveFormat을 사용하는 경우(예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP). |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

프레젠테이션에서 지정된 슬라이드를 페이지 번호를 유지한 상태로 지정된 형식의 파일에 저장하고 추가 옵션을 적용합니다.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | Path to the created file. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 인터페이스 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

프레젠테이션에서 지정된 슬라이드를 페이지 번호를 유지한 상태로 지정된 형식의 스트림에 저장합니다.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

프레젠테이션에서 지정된 슬라이드를 페이지 번호를 유지한 상태로 지정된 형식의 스트림에 저장하고 추가 옵션을 적용합니다.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | Output stream. |
| slides | Int32[] | Array with slide positions, starting from 1. |
| format | SaveFormat | Format of the exported data. |
| options | ISaveOptions | Additional format options. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | stream 또는 slides 매개변수가 null인 경우. |
| ArgumentOutOfRangeException | slides 매개변수에 잘못된 페이지 번호가 포함된 경우. |
| InvalidOperationException | 지원되지 않는 SaveFormat을 사용하는 경우(예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP). |

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

다음 예제는 사용자 지정 차원으로 PowerPoint를 PNG로 변환하는 방법을 보여줍니다.

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

다음 예제는 사용자 지정 크기로 PowerPoint를 PNG로 변환하는 방법을 보여줍니다.

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

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* 인터페이스 [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* 클래스 [Presentation](../../presentation)
* 네임스페이스 [Aspose.Slides](../../presentation)
* 어셈블리 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->