---
title: Add()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 컬렉션의 끝에 서명을 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/idigitalsignaturecollection/add/
---
## IDigitalSignatureCollection::Add(System::SharedPtr\<IDigitalSignature\>) 메서드

컬렉션의 끝에 서명을 추가합니다.

```cpp
virtual void Aspose::Slides::IDigitalSignatureCollection::Add(System::SharedPtr<IDigitalSignature> digitalSignature)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| digitalSignature | [System::SharedPtr](../../../system/sharedptr/)\<[IDigitalSignature](../../idigitalsignature/)\> | 추가할 서명. |
## 비고

```cpp
auto pres = System::MakeObject<Presentation>();
auto signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
signature->set_Comments(u"Aspose.Slides digital signing test.");
pres->get_DigitalSignatures()->Add(signature);
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDigitalSignature](../../idigitalsignature/)
* 클래스 [IDigitalSignatureCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)