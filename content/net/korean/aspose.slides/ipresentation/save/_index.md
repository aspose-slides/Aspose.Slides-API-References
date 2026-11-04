---
title: Save
second_title: Aspose.Sildes for .NET API 레퍼런스
description: 프레젠테이션의 모든 슬라이드를 지정된 형식의 파일에 저장합니다.
type: docs
weight: 390
url: /ko/aspose.slides/ipresentation/save/
---
## Save(string, SaveFormat) {#save_5}

프레젠테이션의 모든 슬라이드를 지정된 형식의 파일에 저장합니다.

```csharp
public void Save(string fname, SaveFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | 생성된 파일의 경로. |
| format | SaveFormat | 내보낸 데이터의 형식. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat) {#save_1}

프레젠테이션의 모든 슬라이드를 지정된 형식의 스트림에 저장합니다.

```csharp
public void Save(Stream stream, SaveFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | 출력 스트림. |
| format | SaveFormat | 내보낸 데이터의 형식. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, SaveFormat, ISaveOptions) {#save_6}

프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션과 함께 파일에 저장합니다.

```csharp
public void Save(string fname, SaveFormat format, ISaveOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | 생성된 파일의 경로. |
| format | SaveFormat | 내보낸 데이터의 형식. |
| options | ISaveOptions | 추가 형식 옵션. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, SaveFormat, ISaveOptions) {#save_2}

프레젠테이션의 모든 슬라이드를 지정된 형식 및 추가 옵션과 함께 스트림에 저장합니다.

```csharp
public void Save(Stream stream, SaveFormat format, ISaveOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | 출력 스트림. |
| format | SaveFormat | 내보낸 데이터의 형식. |
| options | ISaveOptions | 추가 형식 옵션. |

### 예외

| exception | condition |
| --- | --- |
| NotSupportedException | 암호화된 파일을 Office 2007-2010이 아닌 형식으로 저장하려 할 경우 |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat) {#save_7}

프레젠테이션의 지정된 슬라이드를 지정된 형식의 파일에 저장합니다.

```csharp
public void Save(string fname, int[] slides, SaveFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | 생성된 파일의 경로. |
| slides | Int32[] | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | SaveFormat | 내보낸 데이터의 형식. |

### 예외

| exception | condition |
| --- | --- |
| ArgumentNullException | stream 또는 slides 매개변수가 null인 경우. |
| ArgumentOutOfRangeException | slides 매개변수에 잘못된 페이지 번호가 포함된 경우. |
| InvalidOperationException | 지원되지 않는 SaveFormat을 사용하는 경우, 예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(string, int[], SaveFormat, ISaveOptions) {#save_8}

프레젠테이션의 지정된 슬라이드를 지정된 형식 및 추가 옵션과 함께 파일에 저장합니다.

```csharp
public void Save(string fname, int[] slides, SaveFormat format, ISaveOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fname | String | 생성된 파일의 경로. |
| slides | Int32[] | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | SaveFormat | 내보낸 데이터의 형식. |
| options | ISaveOptions | 추가 형식 옵션. |

### 예외

| exception | condition |
| --- | --- |
| ArgumentNullException | stream 또는 slides 매개변수가 null인 경우. |
| ArgumentOutOfRangeException | slides 매개변수에 잘못된 페이지 번호가 포함된 경우. |
| InvalidOperationException | 지원되지 않는 SaveFormat을 사용하는 경우, 예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat) {#save_3}

프레젠테이션의 지정된 슬라이드를 지정된 형식의 스트림에 저장합니다.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | 출력 스트림. |
| slides | Int32[] | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | SaveFormat | 내보낸 데이터의 형식. |

### 예외

| exception | condition |
| --- | --- |
| ArgumentNullException | stream 또는 slides 매개변수가 null인 경우. |
| ArgumentOutOfRangeException | slides 매개변수에 잘못된 페이지 번호가 포함된 경우. |
| InvalidOperationException | 지원되지 않는 SaveFormat을 사용하는 경우, 예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

---

## Save(Stream, int[], SaveFormat, ISaveOptions) {#save_4}

프레젠테이션의 지정된 슬라이드를 지정된 형식 및 추가 옵션과 함께 스트림에 저장합니다.

```csharp
public void Save(Stream stream, int[] slides, SaveFormat format, ISaveOptions options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | Stream | 출력 스트림. |
| slides | Int32[] | 슬라이드 위치 배열, 1부터 시작합니다. |
| format | SaveFormat | 내보낸 데이터의 형식. |
| options | ISaveOptions | 추가 형식 옵션. |

### 예외

| exception | condition |
| --- | --- |
| ArgumentNullException | stream 또는 slides 매개변수가 null인 경우. |
| ArgumentOutOfRangeException | slides 매개변수에 잘못된 페이지 번호가 포함된 경우. |
| InvalidOperationException | 지원되지 않는 SaveFormat을 사용하는 경우, 예: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |

### 참조

* enum [SaveFormat](../../../aspose.slides.export/saveformat)
* interface [ISaveOptions](../../../aspose.slides.export/isaveoptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

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

* interface [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions)
* interface [IPresentation](../../ipresentation)
* namespace [Aspose.Slides](../../ipresentation)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->