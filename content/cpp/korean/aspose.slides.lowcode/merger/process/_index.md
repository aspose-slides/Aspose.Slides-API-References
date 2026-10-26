---
title: Process()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 동일한 형식의 여러 PowerPoint 프레젠테이션을 단일 프레젠테이션 파일로 병합합니다.
type: docs
weight: 1
url: /ko/aspose.slides.lowcode/merger/process/
---
## Merger::Process(System::ArrayPtr\<System::String\>, System::String) 메서드


동일한 형식의 여러 PowerPoint 프레젠테이션을 단일 프레젠테이션 파일로 병합합니다.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| outputFileName | [System::String](../../../system/string/) | 결과로 병합된 프레젠테이션 파일의 출력 파일 이름입니다. |
## 비고




```cpp
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), u"merged.ppt");
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) 메서드


동일한 형식의 여러 PowerPoint 프레젠테이션을 단일 프레젠테이션 파일로 병합합니다.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| outputFileName | [System::String](../../../system/string/) | 결과로 병합된 프레젠테이션 파일의 출력 파일 이름입니다. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 병합된 프레젠테이션이 저장되는 방식을 정의하는 추가 옵션입니다. |
## 비고




```cpp
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.pptx", u"pres2.pptx"}), u"merged.pptx", pptxOptions);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>) 메서드


동일한 형식의 여러 PowerPoint 프레젠테이션을 단일 프레젠테이션 파일로 병합합니다.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 출력 스트림입니다. |
## 비고




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream);
```

## Merger::Process(System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Aspose::Slides::Export::ISaveOptions\>) 메서드


동일한 형식의 여러 PowerPoint 프레젠테이션을 단일 프레젠테이션 파일로 병합합니다.

```cpp
static void Aspose::Slides::LowCode::Merger::Process(System::ArrayPtr<System::String> inputFileNames, System::SharedPtr<System::IO::Stream> outputStream, System::SharedPtr<Aspose::Slides::Export::ISaveOptions> options)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| inputFileNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 입력 프레젠테이션 파일 이름들의 배열입니다. |
| outputStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 출력 스트림입니다. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | 병합된 프레젠테이션이 저장되는 방식을 정의하는 추가 옵션입니다. |
## 비고




```cpp
auto stream = System::MakeObject<System::IO::MemoryStream>();
auto pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
Merger::Process(System::MakeArray<System::String>({u"pres1.ppt", u"pres2.ppt"}), stream, pptxOptions);
```

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Merger](../)
* Class [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)