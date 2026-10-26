---
title: IBlobManagementOptions
second_title: Aspose.Slides for C++ API 레퍼런스
description: Binary Large Object (BLOB)는 단일 엔터티로 저장되는 바이너리 데이터이며, 즉 BLOB는 오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다. 프레젠테이션에 이미 저장되어 있거나 나중에 프로그래밍을 통해 추가될 수 있는 BLOB를 다룰 때 메모리 사용량을 최적화하기 위해 여러 기술이 사용됩니다. IBlobManagementOptions를 사용하면 IPresentation 인스턴스 수명 동안 BLOB 처리와 관련된 다양한 동작 측면을 변경할 수 있습니다.
type: docs
weight: 1535
url: /ko/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions 클래스

Binary Large Object (BLOB)는 단일 엔터티로 저장되는 바이너리 데이터이며, 즉 BLOB는 오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다. 프레젠테이션에 이미 저장되어 있거나 프로그래밍을 통해 나중에 추가될 수 있는 BLOB를 사용할 때 메모리 사용량을 최적화하는 여러 기술이 사용됩니다. [IBlobManagementOptions](./)을(를) 사용하면 [IPresentation](../ipresentation/) 인스턴스 수명 동안 BLOB 처리와 관련된 다양한 동작 측면을 변경할 수 있습니다.

```cpp
class IBlobManagementOptions : public virtual System::Object
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미 체계를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 레퍼런스 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동 소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, C# 스타일 부동 소수점 비교를 에뮬레이트하여 두 NaN을 동일하게 간주합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| virtual **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() | 이 속성은 BLOB를 다룰 때 임시 파일을 생성할 수 있는지 정의합니다. 이는 메모리 사용량을 크게 감소시키지만 파일 생성 권한이 필요합니다. |
| virtual **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() | 메모리 내에 모든 BLOB가 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB가 메모리로 로드되며, 이 제한에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB를 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 높아질 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오. |
| virtual [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() | 이 속성은 [Presentation](../presentation/) 클래스의 인스턴스가 인스턴스 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB를 다룰 때 메모리 사용량과 성능을 향상시키지만, [Presentation](../presentation/)의 인스턴스 수명 동안 소스(스트림 또는 파일)를 변경할 수 없습니다. 예시: |
| virtual [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() | 임시 파일이 생성될 루트 경로입니다. 기본적으로 [System](../../system/) 임시 디렉터리가 사용됩니다. 호스팅 프로세스는 해당 위치에 파일 및 폴더를 생성할 권한이 있어야 합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 레퍼런스 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType에 의해 설명된 유형의 인스턴스인지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문을 구현한 잠금을 수행합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 유형의 복제를 가능하게 합니다. |
| [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 서브클래스 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 레퍼런스로 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체를 nullptr와 레퍼런스 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 공유 레퍼런스 카운트를 지정된 값만큼 감소시킵니다. |
| virtual void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) | 이 속성은 BLOB를 다룰 때 임시 파일을 생성할 수 있는지 정의합니다. 이는 메모리 사용량을 크게 감소시키지만 파일 생성 권한이 필요합니다. |
| virtual void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) | 메모리 내에 모든 BLOB가 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB가 메모리로 로드되며, 이 제한에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB를 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 높아질 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오. |
| virtual void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) | 이 속성은 [Presentation](../presentation/) 클래스의 인스턴스가 인스턴스 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB를 다룰 때 메모리 사용량과 성능을 향상시키지만, [Presentation](../presentation/)의 인스턴스 수명 동안 소스(스트림 또는 파일)를 변경할 수 없습니다. 예시: |
| virtual void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) | 임시 파일이 생성될 루트 경로입니다. 기본적으로 [System](../../system/) 임시 디렉터리가 사용됩니다. 호스팅 프로세스는 해당 위치에 파일 및 폴더를 생성할 권한이 있어야 합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 대신 약한 포인터로 설정합니다. 컨테이너에서 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있습니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구성을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 스마트 포인터나 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 참고

* 클래스 [Object](../../system/object/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)