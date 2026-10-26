---
title: LoadExternalFonts()
second_title: Aspose.Slides C++ API 참조
description: 글꼴을 검색하기 위한 추가 폴더를 추가합니다.
type: docs
weight: 1
url: /ko/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) 메서드

글꼴을 검색할 추가 폴더를 추가합니다.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | 추가 글꼴을 읽을 디렉터리. |
## 비고

다음 예제는 .TTF 파일에서 사용자 정의 글꼴을 로드하는 방법을 보여줍니다.
```cpp
// 문서 디렉터리 경로.
System::String dataDir = u"C:\\";

// 글꼴을 검색할 폴더
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// 사용자 정의 글꼴 디렉터리의 글꼴을 로드합니다
FontsLoader::LoadExternalFonts(folders);

// 작업을 수행하고 프레젠테이션/슬라이드 렌더링을 실행합니다
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// 글꼴 캐시를 지웁니다
FontsLoader::ClearCache();
```

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontsLoader](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)