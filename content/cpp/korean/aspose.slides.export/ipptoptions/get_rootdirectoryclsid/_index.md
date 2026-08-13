---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides C++ API 레퍼런스
description: 루트 디렉터리 항목에 저장된 객체 클래스 GUID(CLSID)를 나타냅니다. 문서 애플리케이션의 COM 활성화에 사용할 수 있습니다. 기본값은 '64818D11-4F9B-11CF-86EA-00AA00B929E8'이며 'Microsoft Powerpoint.Slide.8'에 해당합니다.
type: docs
weight: 1
url: /ko/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() 메서드

루트 디렉터리 항목에 저장된 객체 클래스 GUID(CLSID)를 나타냅니다. 문서 애플리케이션의 COM 활성화에 사용할 수 있습니다. 기본값은 '64818D11-4F9B-11CF-86EA-00AA00B929E8'이며 'Microsoft Powerpoint.Slide.8'에 해당합니다.

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
```

## 비고

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```

## 참조

* 클래스 [Guid](../../../system/guid/)
* 클래스 [IPptOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)