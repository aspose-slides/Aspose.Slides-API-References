---
title: PresentationLockingBehavior enumeration
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior 열거형

로드 및 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 인스턴스를 사용할 때 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 소스(파일 또는 **io.RawIOBase**)를 처리하는 동작을 나타냅니다.

PresentationLockingBehavior 형식은 다음 멤버를 노출합니다:

## 필드

| 필드 | 설명 |
| :- | :- |
| LOAD_AND_RELEASE | 소스는 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 생성자 실행 기간 동안만 잠깁니다.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed)가 false 로 설정된 경우, 모든 BLOB이 <br/>            메모리로 로드됩니다. 그렇지 않으면 임시 파일과 같은 다른 방법이 사용될 수 있습니다. 이 동작은 [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/ko/aspose.slides/presentationlockingbehavior/KEEP_LOCKED)보다 느리며, 소스의 소유권을 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)에 전달할 수 있는 경우 [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/ko/aspose.slides/presentationlockingbehavior/KEEP_LOCKED)를 사용하는 것이 권장됩니다. |
| KEEP_LOCKED | 소스는 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 인스턴스의 전체 수명 동안 잠겨 있으며, 폐기될 때까지 유지됩니다.<br/>            이 동작을 사용하려면 [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed)는 true 로 설정되어야 하며, 그렇지 않으면 예외가 발생합니다. 이 동작은 권장되며, [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/ko/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE)보다 빠르고 메모리 사용량이 적습니다. |


### 비고

소스는 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 생성자에 전달되는 매개변수입니다. 아래 예시에서 소스는 "pres.pptx" 파일입니다:

이 예시에서 소스("pres.pptx" 파일)는 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 인스턴스 수명 동안 잠겨 있으므로, 다른 프로세스에서 변경하거나 삭제할 수 없습니다.


### 참조
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)