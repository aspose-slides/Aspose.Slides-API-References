---
title: ToPdf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Presentation을 PDF로 변환합니다.
type: docs
weight: 14
url: /ko/aspose.slides.lowcode/convert/topdf/
---
## Convert::ToPdf(System::String, System::String) 메서드


[Presentation](../../../aspose.slides/presentation/)을(를) PDF로 변환합니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 입력 프레젠테이션 경로 |
| outPath | [System::String](../../../system/string/) | 출력 경로 |
## 비고




```cpp
Convert::ToPdf(u"pres.pptx", u"pres.pdf");
```

## Convert::ToPdf(System::String, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) 메서드


[Presentation](../../../aspose.slides/presentation/)을(를) PDF로 변환합니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::String presPath, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| presPath | [System::String](../../../system/string/) | 입력 프레젠테이션 경로 |
| outPath | [System::String](../../../system/string/) | 출력 경로 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | 출력 PDF 옵션 |
## 비고




```cpp
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(u"pres.pptx", u"pres.pdf", pdfOptions);
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String) 메서드


[Presentation](../../../aspose.slides/presentation/)을(를) PDF로 변환합니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션 |
| outPath | [System::String](../../../system/string/) | 출력 경로 |
## 비고




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");

Convert::ToPdf(pres, u"output.pdf");
```

## Convert::ToPdf(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::IPdfOptions\>) 메서드


[Presentation](../../../aspose.slides/presentation/)을(를) PDF로 변환합니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPdf(System::SharedPtr<Presentation> pres, System::String outPath, System::SharedPtr<Aspose::Slides::Export::IPdfOptions> options)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션 |
| outPath | [System::String](../../../system/string/) | 출력 경로 |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../../aspose.slides.export/ipdfoptions/)\> | 출력 PDF 옵션 |
## 비고




```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
auto pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->set_Compliance(PdfCompliance::PdfUa);

Convert::ToPdf(pres, u"output.pdf", pdfOptions);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Convert](../)
* 클래스 [IPdfOptions](../../../aspose.slides.export/ipdfoptions/)
* 클래스 [Presentation](../../../aspose.slides/presentation/)
* 네임스페이스 [Aspose::Slides::LowCode](../../)
* 라이브러리 [Aspose.Slides](../../../)