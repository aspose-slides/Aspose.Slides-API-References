---
title: BlobManagementOptions
second_title: Aspose.Slides for C++ API 참조
description: BLOB 처리 규칙 및 기타 BLOB 설정을 관리하는 데 사용할 수 있는 옵션을 나타냅니다.
type: docs
weight: 196
url: /ko/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions 클래스

Represents options which can be used to manage BLOB handling rules and other BLOB settings.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## 메서드

| Method | Description |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | 새 기본 blob management 옵션을 생성합니다. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미를 사용하여 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 모방합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 모방합니다. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도로만 사용됩니다. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | 이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지를 정의합니다. 이는 메모리 사용량을 크게 감소시키지만 파일 생성 권한이 필요합니다. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | 모든 BLOB가 메모리에서 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB가 메모리에 로드됩니다; 이 제한에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB를 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 크게 증가할 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | 이 속성은 [Presentation](../presentation/) 클래스의 인스턴스가 인스턴스 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB 작업 시 메모리 사용량과 성능을 향상시키지만, [Presentation](../presentation/)의 인스턴스 수명 동안 소스(스트림 또는 파일)를 변경할 수 없습니다. |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | 임시 파일이 생성될 루트 경로입니다. 기본적으로 [System](../../system/) 임시 디렉터리가 사용됩니다. 호스팅 프로세스는 해당 위치에 파일 및 폴더를 생성할 권한이 있어야 합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연결된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 유형을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| void [Lock](../../system/object/lock/)() | C# lock() 문 구현을 위한 잠금 기능을 제공합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 타입 복제를 가능하게 합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성하고 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자. 실제로는 아무 것도 복사하지 않고 새 객체를 초기화하며 하위 클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 형식 객체와 nullptr를 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 레퍼런스 카운트를 감소시킵니다. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | 이 속성은 BLOB 작업 중에 임시 파일을 생성할 수 있는지를 정의합니다. 이는 메모리 사용량을 크게 감소시키지만 파일 생성 권한이 필요합니다. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | 모든 BLOB가 메모리에서 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB가 메모리에 로드됩니다; 이 제한에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB를 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 크게 증가할 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | 이 속성은 [Presentation](../presentation/) 클래스의 인스턴스가 인스턴스 수명 동안 소스(파일 또는 스트림)의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 BLOB 작업 시 메모리 사용량과 성능을 향상시키지만, [Presentation](../presentation/)의 인스턴스 수명 동안 소스(스트림 또는 파일)를 변경할 수 없습니다. |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | 임시 파일이 생성될 루트 경로입니다. 기본적으로 [System](../../system/) 임시 디렉터리가 사용됩니다. 호스팅 프로세스는 해당 위치에 파일 및 폴더를 생성할 권한이 있어야 합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 공유 포인터가 아닌 약한 포인터로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 레퍼런스 카운트 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 레퍼런스 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 문 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용하십시오. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 레퍼런스 카운트를 증가시킵니다. 직접 호출해서는 안 되며 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 레퍼런스 카운트를 감소시킵니다. 직접 호출해서는 안 되며 스마트 포인터 또는 ThisProtector를 사용하십시오. |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴하고 모든 내부 데이터 구조를 해제합니다. |

## 참조

* 클래스 [IBlobManagementOptions](../iblobmanagementoptions/)
* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)