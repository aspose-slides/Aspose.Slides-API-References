---
title: AddFromPdf()
second_title: Aspose.Slides for C++ API 참조
description: PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.
type: docs
weight: 183
url: /ko/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) 메서드


PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF 문서에 대한 경로 |

### 반환값

Added slides
## 비고



예: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) 메서드


PDF 문서에서 슬라이드를 생성하고 PDF 가져오기 옵션을 고려하여 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF 문서에 대한 경로 |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF 가져오기 옵션 |

### 반환값

Added slides
## 비고



예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) 메서드


PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | PDF 문서의 소스로 사용할 스트림 |

### 반환값

Added slides
## 비고



예: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) 메서드


PDF 문서에서 슬라이드를 생성하고 컬렉션 끝에 추가합니다.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | PDF 문서의 소스로 사용할 스트림 |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF 가져오기 옵션 |

### 반환값

Added slides
## 비고



예: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// 테이블 감지 설정
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [SlideCollection](../)
* Class [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)